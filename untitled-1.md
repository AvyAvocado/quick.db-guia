---
description: Todo lo necesario para instalar quick.db en tu proyecto
---

# Instalación

Para quick.db necesitarás:

* Node.js v10 o superior
* Un editor de código. No, el bloc de notas no es suficiente. Generalmente se recomienda usar Visual Studio Code, Sublime Text o Atom.

### Requisitos en Linux

En Ubuntu puedes instalar las dependencias para construir la libreria usando build-essential:

```text
sudo apt install build-essential
```

### Requisitos en Windows

Para Windows vas a necesitar instalar Visual Studio, las 'C++ Build Tools' y Python, por suerte puedes instalar todo esto con una simple linea.  
  
Asegurate de escribir esto en una ventana de CMD o Powershell **como Administrador:**

```text
npm install -g windows-build-tools
```

{% hint style="info" %}
La instalación de estas herramientas demora varios minutos.
{% endhint %}

## Instalación

Como cualquier otro package de npm, para instalar debes escribir esto en la ruta de tu proyecto:

```text
npm install --save quick.db
```

