---
type: C4 Component
title: Visit scheduling
status: stable
groma:
  id: visitcontroller
  parent: petclinic-web-app
  code:
    - scanner: java
      file: src/main/java/org/springframework/samples/petclinic/owner/VisitController.java
      symbol: VisitController
  group: Clinic workflows
  technology: Spring MVC
description: Records visits for a pet owner.
---

The visit workflow loads the owner and pet for the form, validates the requested date, adds the visit to the pet, and saves the owner through OwnerRepository.

## Relationships

| Source | Target | Description | Technology |
| --- | --- | --- | --- |
| [src/main/java/org/springframework/samples/petclinic/owner/VisitController.java](../../../../../../src/main/java/org/springframework/samples/petclinic/owner/VisitController.java) | [src/main/java/org/springframework/samples/petclinic/owner/OwnerRepository.java](../../../../../../src/main/java/org/springframework/samples/petclinic/owner/OwnerRepository.java) | Load owners and save visits | Spring dependency injection |
