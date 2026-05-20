## Configuración del proyecto

Crea un archivo `application-dev.properties` a la misma altura que `application.properties` y coloca tus credenciales:

```properties
spring.datasource.username=TU_USUARIO_BD
spring.datasource.password=TU_CONTRA_BD
spring.datasource.url=URL_DE_TU_BD
spring.datasource.driver-class-name=org.postgresql.Driver

spring.mail.host=smtp.gmail.com
spring.mail.port=587
spring.mail.properties.mail.smtp.auth=true
spring.mail.properties.mail.smtp.starttls.enable=true
spring.mail.username=TU_CORREO
spring.mail.password=CONTRA_DE_TU_CORREO
```

````markdown
> ⚠️ No subas este archivo a tu repositorio.
> Agrega `application-dev.properties` al `.gitignore`.