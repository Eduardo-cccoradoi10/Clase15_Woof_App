

# 🐶 Woof App - Clase 15

Proyecto desarrollado en Android Studio utilizando **Jetpack Compose** para la asignatura **Programación 2** de la **Universidad Mariano Gálvez de Guatemala**.

## 👨‍💻 Estudiante

**Carlos Eduardo Corado Ibañez 0905-25-5315**

Universidad Mariano Gálvez de Guatemala

Programación 2

Año: 2026

## 📋 Descripción

Woof es una aplicación que muestra una lista de perros utilizando componentes de Material Design 3. Durante esta práctica se mejoró la interfaz aplicando principios de diseño visual como:

- Paleta de colores personalizada.
- Tarjetas (Cards) para cada elemento de la lista.
- Espaciado consistente mediante dimensiones.
- Soporte para tema claro y oscuro.
- Esquinas redondeadas.
- Tipografías personalizadas.
- Barra superior con logo y nombre de la aplicación.

## ✨ Características implementadas

### 🎨 Diseño visual
- Color principal verde (#006C4C).
- Compatibilidad con modo claro y oscuro.
- Contraste adecuado entre texto y fondo.

### 🃏 Tarjetas
- Cada perro se presenta dentro de una Card.
- Separación visual entre elementos mediante padding.

### 🔵 Imágenes
- Fotografías recortadas con forma circular.
- Uso de `ContentScale.Crop`.

### 🔠 Tipografías personalizadas
- Abril Fatface para títulos.
- Montserrat para textos y contenido.

### 📱 Material Design 3
- Scaffold.
- CenterAlignedTopAppBar.
- MaterialTheme.
- Cards.
- LazyColumn.

## 🛠 Tecnologías utilizadas

- Kotlin
- Android Studio
- Jetpack Compose
- Material Design 3
- Android SDK

## 📂 Estructura principal

```text
app
├── data
│   └── Dog.kt
├── ui.theme
│   ├── Color.kt
│   ├── Theme.kt
│   ├── Shape.kt
│   └── Type.kt
├── MainActivity.kt
└── res
    ├── drawable
    ├── font
    └── values
```

## 📸 Capturas

### Tema Claro
Agregar captura aquí.

### Tema Oscuro
Agregar captura aquí.

## 🎯 Aprendizajes obtenidos

- Uso de MaterialTheme en Jetpack Compose.
- Personalización de temas claros y oscuros.
- Creación de interfaces modernas con Cards.
- Implementación de tipografías personalizadas.
- Uso de Scaffold y TopAppBar.
- Organización visual mediante Shapes y espacios consistentes.

