# Ejercicio
Configurar SonarQube utilizando Docker Compose, para esto necesitas dos servicios:
- Servicio: SonarQube
- Desde el host es necesario acceder a SonarQube por lo que necesitas mapear el puerto correspondiente.
- Servicio: PostgreSQL (existen otras opciones: Microsoft SQL Server, Oracle)
- Coloca un healtcheck para cada uno de los servicios.
- Los dos servicios deben pertenecer a una red de tipo bridge
- Investiga cuáles son los volúmenes necesarios para cada servicio
- Investiga cuáles son las variables de entorno para que los servicios funcionen de manera adecuada.
  
# Una vez creado tu archivo .yaml realiza la respectiva prueba 
```
docker compose up -d
docker compose ps
```

# COMPLETAR CON UNA CAPTURA DE PANTALLA LUEGO DE EJECUTAR EL ARCHIVO
<img width="1919" height="196" alt="image" src="https://github.com/user-attachments/assets/f52ffea9-a9ee-4898-9b97-4c097a561857" />

# ACCEDER A LOCALHOST:puertoDefinido para ingresar a SonarQube
<img width="950" height="462" alt="image" src="https://github.com/user-attachments/assets/be0a75d2-5b69-4f3c-9dc6-a171d720870e" />
