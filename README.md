# Gestor de Eventos Culturales — Java POO

Sistema de gestión de eventos culturales desarrollado en **Java** utilizando **NetBeans**, con persistencia de datos mediante serialización.

El proyecto fue realizado en el contexto de la materia **Programación 2** de la **Universidad Tecnológica Nacional (UTN)**. Su objetivo principal es aplicar conceptos fundamentales de **Programación Orientada a Objetos (POO)**, manejo de archivos, excepciones, colecciones, serialización y exportación de datos.

---

## 🎯 Objetivo del proyecto

El sistema permite administrar eventos culturales, como conciertos y conferencias, aplicando una estructura basada en clases, herencia, polimorfismo, abstracción e interfaces.

Además, incorpora persistencia en archivos binarios, filtros mediante expresiones lambda, generación de estadísticas y exportación de información a distintos formatos.

---

## 🛠️ Funcionalidades principales

### Gestión de eventos

- Alta de eventos culturales.
- Consulta de eventos registrados.
- Modificación de eventos.
- Eliminación de eventos.
- Búsqueda y filtrado de eventos.

### Persistencia de datos

- Guardado de información en archivos binarios.
- Lectura de información previamente guardada.
- Uso de serialización con `ObjectOutputStream` y `ObjectInputStream`.

### Jerarquía de eventos

Uso de clases abstractas, herencia y polimorfismo para representar distintos tipos de eventos.

Estructura principal:

- `Evento`: clase abstracta base.
- `Concierto`: evento derivado.
- `Conferencia`: evento derivado.

### Filtros e interfaz funcional

El sistema permite filtrar eventos utilizando expresiones lambda según distintos criterios, como:

- Fecha.
- Tipo de evento.
- Capacidad restante.

### Estadísticas y exportación

- Generación de estadísticas del sistema.
- Exportación de información en formato texto.
- Exportación de eventos a archivo CSV.
- Generación de información en formato JSON mediante Gson.

### Interfaz gráfica

El proyecto incluye una implementación o extensión gráfica con **JavaFX**, desarrollada como funcionalidad adicional del trabajo.

---

## 🧰 Tecnologías y herramientas utilizadas

- Java
- NetBeans
- Programación Orientada a Objetos
- JavaFX
- Gson
- Serialización de objetos
- Manejo de archivos
- Colecciones
- Expresiones lambda
- Excepciones personalizadas

---

## 📁 Estructura del proyecto

El código se organiza en paquetes para separar responsabilidades:

```text
src/
├── com.cultura.eventos
│   ├── Evento
│   ├── Concierto
│   └── Conferencia
│
├── com.cultura.gestores
│   └── Clases encargadas de gestionar eventos,
│       altas, bajas, modificaciones, filtros y persistencia.
│
└── com.cultura.excepciones
    └── Excepciones personalizadas para manejar errores específicos.
```

---

## ✅ Conceptos aplicados

Este proyecto aplica los siguientes conceptos de programación:

- Clases y objetos.
- Atributos y métodos.
- Constructores y sobrecarga.
- Encapsulamiento.
- Getters y setters con validaciones.
- Herencia.
- Polimorfismo.
- Abstracción.
- Clases y métodos abstractos.
- Interfaces.
- Expresiones lambda.
- Manejo de excepciones.
- Excepciones personalizadas.
- Colecciones como `ArrayList` y `HashMap`.
- Generics.
- Serialización.
- Manejo de archivos.
- Exportación a CSV.
- Conversión a JSON con Gson.
- JavaFX.

---

## ▶️ Cómo ejecutar el proyecto

1. Clonar el repositorio:

```bash
git clone https://github.com/JoaquinCarbonaro/gestor-eventos-culturales-java-poo.git
```

2. Abrir el proyecto con **NetBeans**.

3. Ejecutar la clase principal:

```text
Main.java
```

4. Utilizar el menú disponible para gestionar los eventos culturales.

---

## 📸 UML

El modelado UML del sistema se encuentra incluido en el repositorio como archivo PDF.

---

## ✅ Contexto académico

Este proyecto fue desarrollado como parte de la materia **Programación 2** de la **Universidad Tecnológica Nacional (UTN)**.

El trabajo se enfocó en aplicar conceptos de Programación Orientada a Objetos en un sistema funcional, incorporando persistencia, manejo de archivos, excepciones personalizadas, colecciones, exportación de datos y una estructura organizada por responsabilidades.

---

## 💡 Lo que demuestra este proyecto

Este proyecto demuestra conocimientos en:

- Diseño de clases orientado a objetos.
- Modelado de entidades mediante herencia y abstracción.
- Uso de polimorfismo para trabajar con distintos tipos de eventos.
- Organización del código por paquetes.
- Manejo de persistencia mediante archivos.
- Serialización y deserialización de objetos.
- Validación de datos y uso de excepciones personalizadas.
- Uso de colecciones y generics.
- Exportación de datos a distintos formatos.
- Aplicación de conceptos académicos en un sistema funcional.

---

## 👤 Autor

**Joaquín Carbonaro**

GitHub: https://github.com/JoaquinCarbonaro  
LinkedIn: https://www.linkedin.com/in/joaquin-carbonaro

---

## 🧾 Uso

Este proyecto se comparte con fines educativos y de portfolio. Puede utilizarse como referencia para proyectos académicos relacionados con Java, Programación Orientada a Objetos y manejo de archivos.
