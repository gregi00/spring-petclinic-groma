---
type: C4 Component
title: Welcome page
status: stable
groma:
  id: welcomecontroller
  parent: petclinic-web-app
  code:
    - scanner: java
      file: src/main/java/org/springframework/samples/petclinic/system/WelcomeController.java
      symbol: WelcomeController
  group: Site routes
  technology: Spring MVC, Thymeleaf
description: Serves the clinic application landing page.
---

The root route returns the Thymeleaf welcome template.
