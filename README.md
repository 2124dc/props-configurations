## How to Use Profiles

When deploying or running the service locally or on production, you can specify the profile:

### For Development

You can use the following command:

```bash
mvn spring-boot:run -Dspring-boot.run.profiles=dev
```

Or:

```bash
java -jar cv-auth-service.jar --spring.profiles.active=dev
```

### For Production

You can use the following command:

```bash
mvn spring-boot:run -Dspring-boot.run.profiles=prod
```

Or:

```bash
java -jar cv-auth-service.jar --spring.profiles.active=prod
```
