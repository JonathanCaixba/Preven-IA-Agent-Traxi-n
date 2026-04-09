# 🚚 Customer Health Agent | Traxión

**Hackatón Bécalos Traxión Tech Challenge 2026 - Eje 2: Clientes en Riesgo**

Un dashboard estratégico y motor de decisiones impulsado por IA diseñado para detectar de forma temprana el riesgo de abandono (*churn*) en clientes corporativos e industriales de Traxión. 

Reemplazamos la gestión reactiva con diagnósticos proactivos, cruzando métricas operativas (SLA, NPS, Quejas) con contexto relacional para recomendar acciones concretas mediante *Playbooks* estandarizados.

---

## 🚀 Tecnologías Utilizadas

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JSON](https://img.shields.io/badge/JSON-000000?style=for-the-badge&logo=json&logoColor=white)
![Prompt Engineering](https://img.shields.io/badge/Prompt_Engineering-00C2A8?style=for-the-badge&logo=openai&logoColor=white)

- **Diseño UI/UX** con HTML5 y CSS3 puro (Grid y Flexbox), manteniendo el alcance operativo del reto.
- **Arquitectura de Datos**: JSON Schema estricto para estandarizar entradas (métricas) y salidas (diagnósticos).
- **IA y Lógica de Negocio**: System Prompt estructurado con roles, manejo de incertidumbre y delegación de responsabilidades.
- **Simulación Frontend**: JavaScript nativo ligero para simular tiempos de respuesta de IA en la demo.

---

## 👥 Equipo de Desarrollo

| Foto | Nombre | Rol | Redes |
| :---: | :--- | :--- | :--- |
| <img src="./src/imgs/Caixba.png" width="80" style="border-radius:50%; border: 3px solid #00c2a8;"> | **Jonathan Caixba** | Integración y Frontend | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jonathan-caixba) [![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)](https://github.com/JonathanCaixba) |
| <img src="./src/imgs/FeRubio.jpeg" width="80" style="border-radius:50%; border: 3px solid #00c2a8;"> | **Fernando Rubio** | Lógica de Negocio y Prompting | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](www.linkedin.com/in/fernando-rubio-117b09264) [![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)](https://github.com/Ferr-Oso) |
| <img src="https://ui-avatars.com/api/?name=Axel+Aviles&background=161920&color=00c2a8" width="80" style="border-radius:50%; border: 3px solid #00c2a8;"> | **Axel Aviles** | Estructura de Datos (JSON) | [![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)](https://github.com/Alas200) |

---

## ✨ Características Principales

- **Semáforo de Riesgo Inteligente**: Clasifica clientes en Riesgo Alto, Medio o Bajo no solo por una métrica caída, sino por el cruce de factores (ej. *Churn* silencioso: NPS estable + aumento de cancelaciones + falta de contacto).
- **Manejo de Incertidumbre**: El agente audita la falta de información y ajusta el "Nivel de Confianza", evitando alucinaciones de la IA.
- **Playbooks de Acción Directa**: Genera de 1 a 3 acciones priorizadas con responsables explícitos (Account Manager, Operaciones o Dirección Comercial).
- **Diseño Corporativo Moderno**: Modo oscuro elegante, tipografías monoespaciadas para datos duros y sistema de *badges* para facilitar la lectura ejecutiva.
- **Auditable y Transparente**: La IA siempre justifica su decisión mostrando el peso asignado a cada evidencia.

---

## 📸 Vista Previa

![Vista previa del Customer Health Agent](./src/imgs/preview-traxion.png)

> *Dashboard principal mostrando el análisis en tiempo real de un perfil corporativo en riesgo.*
> <br> by: Equipo ARC🚀