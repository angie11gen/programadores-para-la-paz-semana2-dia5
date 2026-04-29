# Programadores para la Paz – Semana 2 Día 5

## Project Overview
An educational static web project for the "Programadores para la Paz" curriculum. It features a community participation form ("Formulario Participa") built with HTML5 and CSS3, designed to teach students about web accessibility and responsible data collection.

## Project Structure
```
/
├── README.md                       # Project overview and git workflow instructions
├── instrucciones/                  # Instructional materials
│   └── guia-practica-semana2-dia5.txt
└── semana2/                        # Main static site (served as root)
    ├── index.html                  # The participation form
    ├── styles.css                  # Form styling
    ├── checklist-accesibilidad.txt # Accessibility checklist task
    └── reflexion-verificacion.txt  # Reflection task
```

## Technologies
- **HTML5** – Form structure
- **CSS3** – Styling
- **Python 3** – HTTP server for development (`python3 -m http.server 5000 --directory semana2`)

## Running the Project
The workflow "Start application" serves the `semana2/` directory on port 5000 using Python's built-in HTTP server.

## Deployment
Configured as a **static** deployment serving the `semana2/` directory directly.
