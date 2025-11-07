# 🌟 Tarot App

**Tarot App** es una aplicación desarrollada con Android Studio que permite al usuario explorar el tarot de forma interactiva y personalizada. Cada día, el usuario puede sacar hasta **5 cartas únicas**, eliminar hasta **3 que no le resuenen**, y construir su propia **TarotDex** con las cartas descubiertas.

---

## 📱 Características principales

- **Extracción diaria de cartas**  
  El usuario puede sacar hasta **5 cartas distintas por día**, sin repeticiones.  
  Tiene la opción de **eliminar hasta 3 cartas** que no le convenzan, evitando que se repitan ese mismo día.

- **Persistencia y estrategia**  
  Las cartas eliminadas pueden volver a aparecer al día siguiente.  
  Para completar la **TarotDex**, el usuario debe decidir entre aceptar todas las cartas o eliminar estratégicamente.

- **TarotDex**  
  Registro visual de todas las cartas que el usuario ha descubierto.  
  Permite consultar la información completa de cada carta en cualquier momento.

---

## 🧭 Navegación

La app utiliza una **Bottom Navigation Bar** con tres secciones principales:

| Sección               | Descripción |
|-----------------------|-------------|
| **Cartas Diarias**    | Muestra las cartas obtenidas ese día. Al tocar una carta, se despliega su información. Las cartas desaparecen al día siguiente. |
| **TarotDex**          | Visualiza todas las cartas que el usuario ha desbloqueado. Ideal para consulta y seguimiento. |
| **Generador de Cartas** | Permite generar hasta 5 cartas nuevas cada día. |

---

## 🛠️ Estructura técnica

- **Arquitectura Single Activity**  
  Toda la navegación se gestiona desde una única actividad principal.

- **ToolBar dinámica**  
  El título del `ToolBar` se actualiza según la sección en la que se encuentre el usuario.

- **ViewBinding activado**  
  Facilita el acceso seguro a las vistas desde el código.

---

## 🚀 Requisitos

- **Android SDK**: minSdk 27, targetSdk 34 (recomendado)
- **Lenguaje**: Kotlin o Java
- **Entorno**: Android Studio

---

## 📦 Instalación

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tuusuario/tarot-app.git
2. Ábrelo en Android Studio.

3. Sincroniza las dependencias con Gradle.

4. Ejecuta en un emulador o dispositivo físico.

## 🧙‍♀️ Filosofía de uso
La app está diseñada para fomentar la reflexión personal y el descubrimiento. El usuario puede elegir entre aceptar el mensaje del tarot tal como viene, o eliminar cartas que no le resuenen. Esta decisión afecta su progreso en la TarotDex, creando una experiencia única cada día.