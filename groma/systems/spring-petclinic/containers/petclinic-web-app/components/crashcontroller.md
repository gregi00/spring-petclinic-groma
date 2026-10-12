---
type: C4 Component
title: Error demonstration route
status: stable
groma:
  id: crashcontroller
  parent: petclinic-web-app
  code:
    - scanner: java
      file: src/main/java/org/springframework/samples/petclinic/system/CrashController.java
      symbol: CrashController
  group: Site routes
  technology: Spring MVC, Thymeleaf
description: Triggers a deliberate exception for the error-page example.
---

The /oups route throws a RuntimeException so the application can demonstrate its error page.
