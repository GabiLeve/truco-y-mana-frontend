# 🃏 Truco y Maña — Frontend Showcase

> Muestra seleccionada de código y recursos gráficos de mi autoría correspondientes al frontend de **Truco y Maña** (Angular).

> 📌 **Vista general del proyecto:** Podés ver la presentación integral, el despliegue en producción y el contexto del equipo en el repositorio principal: [Truco y Maña — Showcase](https://github.com/GabiLeve/truco-y-mana-showcase).

---

## Alcance de este repositorio
Este repositorio reúne **únicamente una selección de archivos y carpetas** en los que trabajé dentro de `src/` y `public/` con fines de portafolio y demostración de código. **No está pensado para ejecutarse como aplicación completa** ni contiene la totalidad del proyecto del equipo, respetando la privacidad del repositorio grupal y omitiendo configuraciones o entornos sensibles.

---

## 👩‍💻 Enfoque y Aportes en el Frontend

* **Protección de rutas y control de acceso:** Implementación de `authGuard` en **Angular** para resguardar las rutas privadas del sistema y validar el estado de sesión del jugador antes de permitir la navegación.
* **Seguridad en comunicación HTTP:** Desarrollo de un **JWT Interceptor** encargado de interceptar las peticiones salientes hacia la API e inyectar automáticamente el token *Bearer* de autenticación.
* **Gestión de sesión y credenciales:** Implementación de la lógica de cierre de sesión (*logout*) asegurando la limpieza completa de las credenciales y datos sensibles almacenados en `localStorage`.
* **Diseño *Responsive* e Identidad Visual:** Adaptación del *header* principal de la plataforma incorporando el logotipo estándar para escritorio y una versión simplificada optimizada para tablets y dispositivos móviles.

---

## Qué vas a encontrar en este repo

* `src/` — Guards, interceptores HTTP, lógica de autenticación/cierre de sesión y componentes de interfaz (*header* responsive) desarrollados en Angular y TypeScript.
* `public/` — Recursos estáticos y variantes del logotipo utilizadas en la adaptación visual de la cabecera.

---

⌨️ Desarrollado con 🧡 por [GabiLeve](https://github.com/GabiLeve)
