# PRESENTACIÓN PRELIMINAR
## Sistema de Gestión de Convocatorias y Entrevistas
### Terciario Urquiza

#### Equipo
Grupo Análisis  
Integrantes: Algañaras, Nahir | Bottiroli, Ariadna | Oranges, Máximo |  Sánchez, Karen | Palma, Diego  
Versión: 1.0 — Presentación Preliminar (1.er Parcial)  
Fecha: 10 / junio / 2026  
Docente: Pedernera, Pablo  


1. Descripción del sistema y contexto real

En muchas instituciones / organizaciones donde se realizan convocatorias (ya sea laborales, educativas o de prácticas), el proceso de selección suele ser desordenado y poco eficiente.  
Generalmente, los postulantes cargan sus datos, pero luego no existe un seguimiento claro del estado de su postulación, entrevistas o resultados finales. Esto genera confusión tanto para los administradores como para los usuarios.  
A partir de esta problemática, se propone el desarrollo de un sistema web que permita gestionar convocatorias, postulaciones y entrevistas, centralizando toda la información en una única plataforma.  

2. Identificación de stakeholders

Stakeholders internos: el administrador y la empresa  
Administrador:  
Gestiona el sistema completo.  
Crea convocatorias.  
Registra entrevistas.  
Visualiza estadísticas.  
Empresa:  
Publica convocatorias.  
Puede decidir si la postulación es interna o externa.  

Stakeholder externo: el usuario/postulante:  
Usuario/Postulante:  
Se postula a convocatorias.  
Consulta sus postulaciones.  
Visualiza resultados.  

3. Requisitos funcionales y no funcionales

 Funcionales:  
El usuario puede registrarse con el mail institucional y acceder al sistema.  
El usuario puede cargar un CV en formato PDF desde su perfil.  
El usuario puede postularse a convocatorias.  
El sistema utiliza automáticamente el CV cargado por el usuario en cada postulación.  
El sistema valida que no se postule dos veces.  
El sistema valida que el usuario tenga cargado antes un CV para postularse.  
El sistema permite redirigir a un sitio externo.  
El administrador puede: crear convocatorias, evaluar postulantes y registrar entrevistas.  
El sistema muestra resultados al usuario.  
El sistema oculta convocatorias vencidas.  
El sistema muestra estadísticas generales.  

 No Funcionales
El sistema debe ser fácil de usar. (por ejemplo: el proceso de postulación no debe requerir más de 4 pasos una vez que el usuario ha iniciado sesión).  
El sistema deberá restringir el acceso únicamente a usuarios con correos institucionales válidos.  
Debe garantizar seguridad en los datos.  
Debe validar los formularios correctamente.  
Debe ser accesible desde el navegador web.  
Debe actualizar la información en tiempo real.  

4. Historias de usuario

<img width="501" height="701" alt="image" src="https://github.com/user-attachments/assets/41d89b7d-95a2-4d79-a56f-7151f36e83cc" />

5. Casos de uso

<img width="948" height="673" alt="image" src="https://github.com/user-attachments/assets/b18cf9b2-9031-4033-b765-4392eceec0fc" />

6. Modelo Entidad-Relación

--------------------------------------------------
Entidad
Descripción
Usuario
Almacena datos de los postulantes
Empresa
Registra empresas que publican convocatorias
Convocatoria
Contiene información de convocatorias publicadas

Postulación
Registra postulaciones realizadas
Entrevista
Guarda entrevistas y resultados
Administrador
Gestiona el sistema
--------------------------------------------------

<img width="381" height="898" alt="image" src="https://github.com/user-attachments/assets/a4df44c9-4c10-49df-96ec-3f0fa2ff9aac" />

Relaciones:
Un usuario puede realizar muchas postulaciones.
Una convocatoria puede tener muchas postulaciones.
Una empresa puede publicar muchas convocatorias.
Una postulación puede tener una entrevista.
Un administrador puede gestionar múltiples convocatorias y entrevistas.

Ejemplo de atributos:

7. Referencias y fuentes
Apuntes de clase: 
Stakeholders, Requisitos, Técnicas y Métodos: https://docs.google.com/document/d/10MtzGAmCBbhG0Bpe5i3tOR6pRDejYS_kWcTarNB7gkc/edit?tab=t.0
Identificación de Stakeholders y Necesidades en Proyectos Web: https://docs.google.com/document/d/1aRW976EYNBaPYjgdMSkektNe4da0BUBKxSTpEmjaKNk/edit?tab=t.0#heading=h.ef7qf762a8wz
Diagrama Entidad Relación: https://docs.google.com/presentation/d/1r__6Iljgi8iTWQHCk2yEV27reVdGizABsesVVfwjiSw/edit?slide=id.p#slide=id.p
