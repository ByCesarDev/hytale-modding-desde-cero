# 📦 Episodio 01 — Introducción al Modding en Hytale  
## Creando nuestro primer item personalizado

Bienvenido al **Episodio 01** de la serie **“Aprende a crear MODS en Hytale desde CERO”**.

En este episodio damos los **primeros pasos reales en el modding de Hytale**, creando nuestro **primer item personalizado** utilizando el **Asset Editor**, y aprendiendo cómo funciona la **estructura básica de carpetas** que utiliza un mod.

Este episodio es fundamental, ya que aquí se explican las bases que se usarán en **todos los mods** más adelante.

---

## 🎯 Objetivo del episodio

- Crear un mundo de prueba para desarrollo
- Acceder al **Asset Editor**
- Crear un mod desde cero
- Entender la estructura básica de un proyecto
- Crear un **item personalizado (espada)**
- Configurar recursos, texturas e iconos
- Definir textos usando el sistema de idiomas
- Activar correctamente el mod en un mundo

---

## 🧩 ¿Qué se crea en este episodio?

✅ Mundo de desarrollo en creativo  
✅ Mod base usando el Asset Editor  
✅ Primer item personalizado (espada)  
✅ Textura e icono del item  
✅ Archivo de idioma del servidor  
✅ Activación correcta del mod  

---

## 🌍 Creación del mundo de prueba

1. Se crea un **mundo creativo** de prueba.
2. Se desactiva el tiempo para facilitar el desarrollo.
3. Se obtienen permisos **OP** usando el comando `/op self`.
4. Se abre el **Asset Editor** desde el menú de herramientas.

Este mundo se usará **exclusivamente para desarrollo**.

---

## 🧱 Creación del mod en el Asset Editor

1. Desde el Asset Editor se crea un nuevo **Mod Pack**.
2. Se le asigna:
   - Nombre del mod
   - Autor
   - Descripción
3. El mod se guarda y queda listo para agregar contenido.

---

## 🗡 Creación del item personalizado

- Se crea un nuevo **Asset de tipo Item**
- Se copia un item base (una espada existente del juego)
- Se define un **Unique Asset ID**
- Se configuran:
  - Propiedades generales
  - Rendering
  - Icono
  - Rareza
  - Nivel
  - Calidad

Este item sirve como **base para futuros items**, armas o herramientas.

---

## 📂 Estructura del proyecto

```txt
Proyecto/
├── Common/
│   └── Resources/
│       ├── Textures/
│       │   └── Irons/
│       │       └── demonic_sword.png
│       └── Models/ (opcional, para futuros episodios)
└── Server/
    └── Languages/
        └── en-US/
            └── server.lang
```

---

## 📁 Common/

Esta carpeta **no se crea automáticamente** y debe hacerse manualmente.

Contiene todos los recursos compartidos entre cliente y servidor:
- Texturas
- Modelos
- Recursos visuales

> ⚠️ Si las carpetas no tienen el nombre correcto, **Hytale no las detectará**.

---

## 📁 Server / Languages

Actualmente Hytale solo soporta el idioma **inglés (`en-US`)**.

### server.lang

Archivo donde se definen los textos visibles del mod, como nombres y descripciones.

Ejemplo:
```txt
items.demonic-sword.name=Demonic Sword
```

---

## 🎨 Texturas e iconos

- Las texturas se colocan en `Common/Resources/Textures`
- El Asset Editor **no detecta carpetas nuevas en caliente**
- Es necesario:
  - Salir del mundo
  - Volver a entrar
  - Reabrir el Asset Editor

Esto también aplica para los **iconos del item**.

---

## ⚙️ Ajustes del item

Desde el Asset Editor se pueden modificar:
- Rareza
- Nivel
- Calidad
- Durabilidad
- Interacciones

Los cambios se reflejan **directamente en el juego** al volver al mundo.

---

## 📦 Compartir el mod

1. Ve a la carpeta raíz del mod.
2. Comprímelo en un archivo `.zip`.
3. Comparte ese archivo o colócalo en la carpeta `mods`.

---

## ⚠️ Activación correcta del mod

> ❗ **Muy importante**

- Si el mod está en la carpeta global de mods:
  - **NO lo actives en el mundo donde fue creado**
- Esto puede causar:
  - Conflictos
  - Errores
  - Problemas de carga

👉 Usa el mod en **otro mundo** o no lo actives en ese mismo mundo de desarrollo.

---

## 📺 Video del episodio

🎥 **Episodio 01 — Creando nuestro primer item en Hytale**  
[![🔥 Aprende a crear MODS en Hytale desde CERO | Episodio 1: Items personalizados](../assets/imagenes/portada.jpg)](https://www.youtube.com/watch?v=lHEaxneclLY)

Se recomienda **ver el video junto con el proyecto**, ya que se explica paso a paso el razonamiento detrás de cada decisión.

---

## 🚀 Próximo episodio

En el siguiente episodio aprenderemos:
- Cómo crear **bloques personalizados**
- Uso más avanzado del Asset Editor
- Mejor organización de recursos

---

## 📌 Nota final

> La estructura puede cambiar con el desarrollo de Hytale,  
> pero los **conceptos aprendidos aquí seguirán siendo fundamentales**.

⭐ Si este episodio te ayudó, considera apoyar el proyecto ❤️
