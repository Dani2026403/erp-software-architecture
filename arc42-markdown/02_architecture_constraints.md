# 2. Restricciones de Arquitectura

## 2.1 Restricciones Tecnológicas

Para el desarrollo y documentación del Sistema ERP se han definido las siguientes restricciones:

- El **frontend** del sistema será una aplicación web desarrollada con **JavaScript y React**, accesible desde un navegador web.
- El **backend** será desarrollada en **Java**, encargada de la lógica de negocio y la exposición de servicios REST.
- La **base de datos** será **PostgreSQL**, utilizada para el almacenamiento persistente de la información del sistema.
- La comunicación entre frontend y backend se realizará mediante **servicios REST sobre HTTPS**, utilizando formato **JSON**.
- Los diagramas de arquitectura y diseño serán elaborados utilizando **PlantUML**.

---

## 2.2 Restricciones de Herramientas

Las siguientes herramientas han sido definidas como obligatorias para el desarrollo del taller:

- **Jira** o **Notion** para la gestión ágil del proyecto y el manejo del Product Backlog.
- **GitHub** como repositorio público para el control de versiones y la documentación del sistema.
- **PlantUML** para la creación de diagramas UML y C4.
- **arc42** como plantilla base para la documentación de arquitectura.

---

## 2.3 Restricciones Organizacionales y Académicas

- El desarrollo del sistema se realiza con fines **académicos**, por lo cual el alcance funcional está limitado al Módulo de Compras.
- El tiempo de desarrollo está restringido al período definido para el taller.
- La entrega del taller es **individual**, aunque el trabajo pueda realizarse en grupo.
- El sistema no contempla, en esta etapa, aspectos avanzados como alta disponibilidad, escalabilidad masiva o tolerancia a fallos.

---

## 2.4 Convenciones y Estándares

- La documentación de arquitectura se redactará en formato **Markdown**.
- Los nombres de archivos y carpetas seguirán una convención clara y descriptiva.
- Los diagramas exportados se almacenarán en la carpeta `docs/images` del repositorio.
- Se utilizará el idioma **español** para toda la documentación del proyecto.
