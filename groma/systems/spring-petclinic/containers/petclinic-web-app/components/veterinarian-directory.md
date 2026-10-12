---
type: C4 Component
title: Veterinarian directory
status: stable
groma:
  id: veterinarian-directory
  parent: petclinic-web-app
  code:
    - scanner: java
      file: src/main/java/org/springframework/samples/petclinic/vet/VetController.java
      symbol: VetController
    - scanner: java
      file: src/main/java/org/springframework/samples/petclinic/vet/Vets.java
      symbol: Vets
  group: Clinic workflows
  technology: Spring MVC, XML binding
description: Displays veterinarians in an HTML list and data endpoint.
---

Spring MVC handlers page the veterinarian list for the web UI and expose a Vets response populated from VetRepository.

## Relationships

| Source | Target | Description | Technology |
| --- | --- | --- | --- |
| [src/main/java/org/springframework/samples/petclinic/vet/VetController.java](../../../../../../src/main/java/org/springframework/samples/petclinic/vet/VetController.java) | [src/main/java/org/springframework/samples/petclinic/vet/VetRepository.java](../../../../../../src/main/java/org/springframework/samples/petclinic/vet/VetRepository.java) | Read veterinarians | Spring dependency injection |
