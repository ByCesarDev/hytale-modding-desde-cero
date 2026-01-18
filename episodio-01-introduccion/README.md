# 📦 Episodio 01 — Introducción al Modding en Hytale

Bienvenido al **Episodio 01** de la serie **Hytale Modding desde CERO**.

En este episodio damos los **primeros pasos reales en el modding de Hytale**, creando nuestro **primer item personalizado** y entendiendo la **estructura básica de carpetas** que utiliza un proyecto de mod.

Este episodio es clave, ya que aquí se explican las bases sobre las que se construyen todos los mods.

---

## 🎯 Objetivo del episodio

- Entender la estructura base de un proyecto de mod en Hytale
- Saber para qué sirve cada carpeta principal
- Crear un **item personalizado sencillo**
- Aprender cómo se organizan los recursos y los textos del servidor

---

## 🧩 ¿Qué se crea en este episodio?

✅ Estructura base del proyecto  
✅ Primer item personalizado  
✅ Recursos básicos (imágenes / modelos)  
✅ Archivo de idioma del servidor  

---

## 📂 Estructura del proyecto

La estructura utilizada en este episodio es la siguiente:

```txt
Proyecto/
├── Common/
│   └── Resources/
│       └── (subcarpetas y elementos)
│           ├── imágenes
│           ├── modelos
│           └── otros recursos básicos
└── Server/
    └── Languages/
        └── en-US/
            └── server.lang
```

---

## 📁 Explicación de la estructura

### 🔹 Common/
Contiene todo el contenido **compartido** del mod.  
Aquí se definen los recursos que pueden ser usados tanto por el cliente como por el servidor.

#### ▸ Resources/
Dentro de esta carpeta se almacenan los **recursos básicos del mod**, como:
- Imágenes
- Modelos
- Definiciones de items
- Otros elementos visuales o de contenido

La idea es mantener todo bien organizado desde el inicio para que el mod sea escalable.

---

### 🔹 Server/
Contiene archivos que solo afectan al **lado del servidor**.

#### ▸ Languages/
Aquí se definen los idiomas y textos que el servidor utiliza.

#### ▸ en-US/
Carpeta correspondiente al idioma inglés (Estados Unidos).  
Más adelante se podrán agregar otros idiomas siguiendo esta misma estructura.

#### ▸ server.lang
Archivo donde se definen los textos del servidor, como:
- Nombre del item
- Descripciones
- Mensajes relacionados con el mod

---

## 🗡 Item creado en este episodio

En este episodio se crea un **item básico**, con el objetivo de aprender:
- Dónde ubicar sus recursos
- Cómo organizar su información
- Cómo conectar el item con los archivos del proyecto

Este item servirá como base para:
- Armas
- Herramientas
- Items más avanzados en futuros episodios

---

## ⚙️ Activación del mod en el mundo

Una vez que el mod esté listo:

1. Coloca el mod en la carpeta **`mods`** correspondiente.
2. **Actívalo explícitamente en el mundo donde fue creado**.

> ⚠️ Es importante activar el mod únicamente en el mundo correcto para  
> **evitar conflictos**, errores de carga o comportamientos inesperados con otros mundos o mods.

Este paso es fundamental durante el desarrollo y las pruebas.

---

## 📺 Video del episodio

🎥 **Episodio 01 — Introducción y primer item en Hytale**  
👉 *(Agrega aquí el enlace al video cuando esté publicado)*

Se recomienda **ver el video junto con el código**, ya que se explica el razonamiento detrás de cada decisión.

---

## 🧠 Conceptos clave aprendidos

- Cómo se estructura un proyecto de mod en Hytale
- Diferencia entre contenido común y contenido del servidor
- Importancia de una buena organización desde el inicio
- Flujo básico de trabajo para crear contenido
- Activación correcta de mods por mundo

---

## 🚀 Próximo episodio

En el siguiente episodio aprenderemos a:
- Profundizar en la creación de bloques
- Mejorar la organización de recursos
- Ampliar el contenido del mod

---

## 📌 Notas

> ⚠️ La estructura puede evolucionar conforme Hytale avance o cambien las herramientas oficiales,  
> pero los conceptos aprendidos aquí seguirán siendo fundamentales.

---

⭐ Si este episodio te ayudó, considera darle una estrella al repositorio  
Eso apoya muchísimo el proyecto ❤️
