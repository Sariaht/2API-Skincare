# API SKINCARE

##🌿 API de Skincare - Gestión de Productos Cloud Proyecto de Desarrollo de Aplicaciones en la Nube

-📝 Descripción del Proyecto:
Esta aplicación es una solución integral para la gestión de inventarios de productos de cuidado personal (Skincare). Permite realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) sobre un catálogo de productos, integrando un backend robusto en Spring Boot con una base de datos PostgreSQL hospedada en Google Cloud.

-👥 Integrantes y Responsabilidades:

--Sary Ariza Vargas: Configuración de infraestructura en Google Cloud (Cloud SQL, Cloud Run, Artifact Registry), implementación de seguridad en variables de entorno y desarrollo de endpoints en el Backend.

--Adriana Carreño: Diseño y desarrollo de la interfaz de usuario (Frontend), integración de servicios API mediante JavaScript/Fetch y elaboración de la documentación técnica del sistema.

🛠️ Stack Tecnológico Backend: Java 17, Spring Boot, Spring Data JPA.

Base de Datos: PostgreSQL (Google Cloud SQL).

Infraestructura: Google Cloud Platform (GCP).

CI/CD: Google Cloud Build (Despliegue automático).

Frontend: HTML5, CSS3, JavaScript Vanilla.

☁️ Servicios Cloud Implementados Cloud Run: Hosting del contenedor de la API con escalabilidad automática.

Cloud SQL: Instancia administrada de base de datos PostgreSQL.

Artifact Registry: Almacenamiento privado de imágenes de Docker.

Cloud Build: Pipeline para integración y despliegue continuo (CI/CD).
## Verificar instalación de Java y Maven
Ejecuta los siguientes códigos para validar la versiones instaladas
```markdown
> CMD
java -version
mvn -v
```
## Crear archivo Maven

Ve a https://start.spring.io/?utm_source=copilot.com
Configura:
- Project: Maven
- Language: Java
- Spring Boot: última versión estable
- Dependencias: Spring Web, Spring Data JPA, PostgreSQL Driver
- Haz clic en GENERATE, se descargará un .zip
- Extrae el contenido en tu carpeta de trabajo

## Abrir tu proyecto
Dirígete a visual studio code, y abre la carpeta maven que fue generada encontrarás diferentes archivos como se muestra a continuación:
<img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/4ac848b3-7cba-4c1a-a971-478c71007df8" />
