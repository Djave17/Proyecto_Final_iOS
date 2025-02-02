# 📚 AppGestionUAM

Bienvenido a **AppGestionUAM**, una aplicación iOS desarrollada en Swift con arquitectura **MVVM** para la gestión de cursos universitarios. 🚀

---

## 📌 Índice

- [📖 Descripción](#-descripción)
- [📂 Estructura del Proyecto](#-estructura-del-proyecto)
- [🔧 Tecnologías Usadas](#-tecnologías-usadas)
- [📸 Recursos](#-recursos)
- [📜 Licencia](#-licencia)

---

## 📖 Descripción

**AppGestionUAM** permite a los estudiantes explorar cursos universitarios, obtener información detallada, marcar favoritos y gestionar su carga académica.

### 🎯 Funcionalidades principales:
✅ Autenticación de usuarios (Login, Registro)  
✅ Listado y búsqueda de cursos  
✅ Detalle de cada curso con horarios, requisitos y materiales  
✅ Gestión de favoritos  
✅ Creación y edición de cursos (para administradores)  
✅ Persistencia de datos con **UserDefaults**  
✅ Soporte multimedia (videos e imágenes)  

---

## 📂 Estructura del Proyecto

La aplicación sigue una estructura organizada basada en **MVVM**:

📁 [`AppGestionUAM`](https://github.com/Djave17/Proyecto_Final_iOS/tree/main/AppGestionUAM)  *(Carpeta raíz del código fuente)*

- 📂 [`ViewControllers`](https://github.com/Djave17/Proyecto_Final_iOS/tree/main/AppGestionUAM/AppGestionUAM/Views) → Controladores de UI y navegación.
- 📂 [`ViewModels`](https://github.com/Djave17/Proyecto_Final_iOS/tree/main/AppGestionUAM/AppGestionUAM/ViewModels) → Lógica de negocio y conexión entre UI y Modelos.
- 📂 [`Models`](https://github.com/Djave17/Proyecto_Final_iOS/tree/main/AppGestionUAM/AppGestionUAM/Models) → Definición de estructuras de datos (`Course`, `User`, etc.).
- 📂 [`Networking`](https://github.com/Djave17/Proyecto_Final_iOS/tree/main/AppGestionUAM/AppGestionUAM/Networking%20) → Comunicación con la API REST.
- 📂 [`Persistance`](https://github.com/Djave17/Proyecto_Final_iOS/tree/main/AppGestionUAM/AppGestionUAM/Persistance) → Gestión de favoritos con `UserDefaults/CoreData`.
- 📂 [`Extensiones`](https://github.com/Djave17/Proyecto_Final_iOS/tree/main/AppGestionUAM/AppGestionUAM/Extensiones) → Métodos adicionales para mejorar `UIViewController`.
- 📂 [`Resources`](https://github.com/Djave17/Proyecto_Final_iOS/tree/main/AppGestionUAM/Resources) → Imágenes, sonidos (`agua.mp3`), y videos (`vd_Onb1.mov`, `vd_Onb2.mov`, `vd_Onb3.mov`).
- 📂 [`Tests`](https://github.com/Djave17/Proyecto_Final_iOS/tree/main/AppGestionUAM/AppGestionUAMTests) → Pruebas unitarias y de UI.

---

## 🔧 Tecnologías Usadas

- **Swift** 🚀
- **UIKit & Storyboards** 🎨
- **MVVM Architecture** 🏗️
- **URLSession** 🌐
- **IQKeyboardManager** 🎹 (Para mejorar la interacción con el teclado)
- **UserDefaults** 💾 (Persistencia de datos)

---

## 📸 Recursos

- 🔊 [`agua.mp3`](https://github.com/Djave17/Proyecto_Final_iOS/tree/main/AppGestionUAM/Resources) (Efecto de sonido)
- 🎥 [`vd_Onb1.mov`](https://github.com/Djave17/Proyecto_Final_iOS/blob/main/AppGestionUAM/AppGestionUAM/vd_Onb1.mov)
- 🎥 [`vd_Onb2.mov`](https://github.com/Djave17/Proyecto_Final_iOS/blob/main/AppGestionUAM/AppGestionUAM/vd_Onb2.mov))
- 🎥 [`vd_Onb3.mov`](https://github.com/Djave17/Proyecto_Final_iOS/blob/main/AppGestionUAM/AppGestionUAM/vd_Onb3.mov)

---

## 📜 Licencia

Este proyecto es de uso académico y está sujeto a los términos de la Universidad Autónoma Metropolitana (UAM).
