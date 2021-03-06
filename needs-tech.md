# Visit-counter technical needs

Scenario: Recover across restarts of the server
that runs the visit-counter

  Given : Server stores the recent counter value in a pointer before shutdown,
  manual logging done in case of server failure.
  When : Server restarts.
  Then : Manually increment counter with present value, switch it to automatic mode.

Scenario: Reconcile counts if the sensor is offline for a while

  Given : Sensor stores the recent count values in pointers before shutdown,
  manual logging done when sensor goes offline.
  When : Sensor restarts.
  Then : Manually increment counters with present values, switch it to
  automatic mode.
