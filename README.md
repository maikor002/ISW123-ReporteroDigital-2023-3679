# ISW123-ReporteroDigital-2023-3679

Aplicación de consola en C# desarrollada como parte de la asignación **Reportero Digital**, cuyo objetivo es simular el ensamblaje de un artículo periodístico combinando múltiples fuentes de información de forma asíncrona y en paralelo.

## 📌 Descripción del proyecto

El sistema obtiene de manera simultánea:
- El texto de la noticia
- Las imágenes relacionadas
- El análisis periodístico

Cada proceso se ejecuta de forma asíncrona utilizando `async`, `await` y `Task.WhenAll`, notificando su finalización mediante eventos.  
Además, la aplicación es resistente a fallos gracias al uso de una excepción personalizada.

## 🧠 Conceptos aplicados

- Programación asíncrona (`async / await`)
- Paralelismo de tareas (`Task.WhenAll`)
- Manejo de eventos (`event Action<string>`)
- Manejo de excepciones personalizadas (`try / catch`)
- Buenas prácticas de commits en GitHub

## 🛠️ Tecnologías utilizadas

- Lenguaje: C#
- Plataforma: .NET
- Tipo de aplicación: Consola

## ▶️ Cómo ejecutar el proyecto

1. Clonar el repositorio desde GitHub  
2. Abrir el proyecto en Visual Studio  
3. Ejecutar la aplicación con **Ctrl + F5**

## 👤 Autor

- **Nombre:** Maikro Adonis  
- **Matrícula:** 2023-3679  

## 📂 Repositorio

Este proyecto contiene un mínimo de **5 commits**, mostrando el progreso real del desarrollo, tal como lo requiere la asignación.
