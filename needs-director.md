# Visit-counter for a Director

## Scenario: Show patient visits during working days and holidays

  - Given: Patient visit.
  - When: On working days and holidays.
  - Then: Count footfalls. 
          Issue patient card to patient, visitor card to visitors.
          Amenities to patient by director.
          Seating arrangement by reception.
          Parking facilities by watchmen. 

## Scenario: Compute parking slots to reserve for visiting specialists

  - Given: Specialists visit.
  - When: Scheduled time.
  - Then: Reserve the parking slots for specialists.
