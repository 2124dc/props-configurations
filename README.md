### How to Activate a Profile:

To activate a profile when running your application, you can use the following options:

- **Using Command Line Arguments:**

  ```bash
  java -jar cv-auth-server.jar --spring.profiles.active=dev
  ```

  or

  ```bash
  java -jar cv-auth-server.jar --spring.profiles.active=prod
  ```

- **Using Maven:**

  ```bash
  mvn spring-boot:run -Dspring-boot.run.profiles=dev
  ```

  or

  ```bash
  mvn spring-boot:run -Dspring-boot.run.profiles=prod
  ```
