tcae-sas-app/
├── public/
│   ├── index.html
│   ├── manifest.json
│   ├── icon-192.png
│   ├── icon-512.png
│   └── screenshots/
│       ├── flashcards.png
│       ├── simulacro.png
│       ├── progreso.png
│       ├── planner.png
│       └── perfil.png
│
├── src/
│   ├── App.jsx
│   ├── index.js
│   ├── serviceWorkerRegistration.js
│   ├── components/
│   │   ├── Flashcard.jsx
│   │   ├── Simulacro.jsx
│   │   ├── Progreso.jsx
│   │   ├── Planner.jsx
│   │   └── Perfil.jsx
│   ├── pages/
│   │   ├── Home.jsx
│   │   ├── Estudio.jsx
│   │   ├── Examen.jsx
│   │   ├── Progreso.jsx
│   │   └── Perfil.jsx
│   ├── data/
│   │   ├── temarios.json
│   │   ├── flashcards.json
│   │   ├── simulacro1.json
│   │   └── tips.json
│   └── styles/
│       └── app.css
│
├── package.json
├── README.md
└── .gitignore
/node_modules
/build
.env
.env.local
.env.development.local
.env.test.local
.env.production.local
.DS_Store
Thumbs.db
.vscode/
.idea/
---

## 🚀 Comandos básicos para GitHub (en Termux o PC)

```bash
# Clonar el repositorio
git clone https://github.com/tuusuario/tcae-sas-app.git
cd tcae-sas-app

# Subir proyecto inicial
git add .
git commit -m "Proyecto inicial TCAE SAS"
git branch -M main
git push -u origin main

# Instalar dependencias
npm install

# Desplegar en GitHub Pages
npm run build
npm run deploy
tcae-sas-app/
├── public/
│   ├── index.html
│   ├── manifest.json
│   ├── icon-192.png
│   ├── icon-512.png
│
├── src/
│   ├── App.jsx
│   ├── index.js
│   └── styles/
│       └── app.css
│
├── package.json
├── README.md
└── .gitignore
/node_modules
/build
.env
.DS_Store
Thumbs.db
.vscode/
.idea/
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>TCAE SAS App</title>
    <link rel="manifest" href="manifest.json" />
    <link rel="icon" href="icon-192.png" />
  </head>
  <body>
    <div id="root"></div>
  </body>
</html>
import React from "react";
import "./styles/app.css";

function App() {
  return (
    <div className="App">
      <h1>TCAE SAS App</h1>
      <p>Bienvenida Lourdes 👋. Esta es tu aplicación para preparar las oposiciones TCAE.</p>
    </div>
  );
}

export default App;
import React from "react";
import ReactDOM from "react-dom/client";
import App from "./App";

const root = ReactDOM.createRoot(document.getElementById("root"));
root.render(<App />);
body {
  font-family: Arial, sans-serif;
  background-color: #fdf6f9;
  margin: 0;
  padding: 0;
}

.App {
  text-align: center;
  padding: 2rem;
}

h1 {
  color: #d17ba3;
}
{
  "name": "tcae-sas-app",
  "version": "1.0.0",
  "private": true,
  "homepage": "https://tuusuario.github.io/tcae-sas-app",
  "dependencies": {
    "react": "^18.0.0",
    "react-dom": "^18.0.0",
    "react-scripts": "5.0.1"
  },
  "devDependencies": {
    "gh-pages": "^6.0.0"
  },
  "scripts": {
    "start": "react-scripts start",
    "build": "react-scripts build",
    "predeploy": "npm run build",
    "deploy": "gh-pages -d build"
  }
}
# TCAE SAS App

Aplicación web y PWA para preparar las oposiciones de **Técnico en Cuidados Auxiliares de Enfermería (SAS)**.

## 🚀 Instalación

```bash
git clone https://github.com/tuusuario/tcae-sas-app.git
cd tcae-sas-app
npm install
npm start
npm run build
npm run deploy
---

## 🚀 Comandos básicos en Termux

```bash
# Clonar el repositorio
git clone https://github.com/tuusuario/tcae-sas-app.git
cd tcae-sas-app

# Subir proyecto inicial
git add .
git commit -m "Proyecto inicial TCAE SAS"
git branch -M main
git push -u origin main

# Instalar dependencias
npm install

# Desplegar en GitHub Pages
npm run build
npm run deploy
tcae-sas-app/
├── public/
│   ├── index.html
│   ├── manifest.json
│   ├── icon-192.png
│   ├── icon-512.png
│
├── src/
│   ├── App.jsx
│   ├── index.js
│   └── styles/
│       └── app.css
│
├── package.json
├── README.md
└── .gitignore
/node_modules
/build
.env
.DS_Store
Thumbs.db
.vscode/
.idea/
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>TCAE SAS App</title>
    <link rel="manifest" href="manifest.json" />
    <link rel="icon" href="icon-192.png" />
  </head>
  <body>
    <div id="root"></div>
  </body>
</html>
import React from "react";
import "./styles/app.css";

function App() {
  return (
    <div className="App">
      <h1>TCAE SAS App</h1>
      <p>Bienvenida Lourdes 👋. Esta es tu aplicación para preparar las oposiciones TCAE.</p>
    </div>
  );
}

export default App;
import React from "react";
import ReactDOM from "react-dom/client";
import App from "./App";

const root = ReactDOM.createRoot(document.getElementById("root"));
root.render(<App />);
body {
  font-family: Arial, sans-serif;
  background-color: #fdf6f9;
  margin: 0;
  padding: 0;
}

.App {
  text-align: center;
  padding: 2rem;
}

h1 {
  color: #d17ba3;
}
{
  "short_name": "TCAE",
  "name": "TCAE SAS App",
  "icons": [
    {
      "src": "icon-192.png",
      "sizes": "192x192",
      "type": "image/png"
    },
    {
      "src": "icon-512.png",
      "sizes": "512x512",
      "type": "image/png"
    }
  ],
  "start_url": ".",
  "display": "standalone",
  "theme_color": "#d17ba3",
  "background_color": "#fdf6f9"
}
{
  "name": "tcae-sas-app",
  "version": "1.0.0",
  "private": true,
  "homepage": "https://tuusuario.github.io/tcae-sas-app",
  "dependencies": {
    "react": "^18.0.0",
    "react-dom": "^18.0.0",
    "react-scripts": "5.0.1"
  },
  "devDependencies": {
    "gh-pages": "^6.0.0"
  },
  "scripts": {
    "start": "react-scripts start",
    "build": "react-scripts build",
    "predeploy": "npm run build",
    "deploy": "gh-pages -d build"
  }
}
# TCAE SAS App

Aplicación web y PWA para preparar las oposiciones de **Técnico en Cuidados Auxiliares de Enfermería (SAS)**.

---

## 🚀 Instalación

```bash
git clone https://github.com/tuusuario/tcae-sas-app.git
cd tcae-sas-app
npm install
npm start
npm run build
npm run deploy
---

## 🚀 Comandos básicos en Termux

```bash
# Clonar el repositorio
git clone https://github.com/tuusuario/tcae-sas-app.git
cd tcae-sas-app

# Subir proyecto inicial
git add .
git commit -m "Proyecto inicial TCAE SAS"
git branch -M main
git push -u origin main

# Instalar dependencias
npm install

# Desplegar en GitHub Pages
npm run build
npm run deploy
src/
├── components/
│   ├── Flashcard.jsx
│   └── Simulacro.jsx
import React, { useState } from "react";
import "../styles/app.css";

function Flashcard({ pregunta, respuesta }) {
  const [mostrarRespuesta, setMostrarRespuesta] = useState(false);

  return (
    <div className="flashcard" onClick={() => setMostrarRespuesta(!mostrarRespuesta)}>
      <p>{mostrarRespuesta ? respuesta : pregunta}</p>
    </div>
  );
}

export default Flashcard;
import React, { useState } from "react";

function Simulacro({ preguntas }) {
  const [indice, setIndice] = useState(0);
  const [aciertos, setAciertos] = useState(0);

  const responder = (correcta) => {
    if (correcta) setAciertos(aciertos + 1);
    setIndice(indice + 1);
  };

  if (indice >= preguntas.length) {
    return (
      <div>
        <h2>Resultado del simulacro</h2>
        <p>Has acertado {aciertos} de {preguntas.length} preguntas.</p>
      </div>
    );
  }

  const preguntaActual = preguntas[indice];

  return (
    <div>
      <h2>Simulacro de examen</h2>
      <p>{preguntaActual.texto}</p>
      {preguntaActual.opciones.map((opcion, i) => (
        <button key={i} onClick={() => responder(opcion.correcta)}>
          {opcion.texto}
        </button>
      ))}
    </div>
  );
}

export default Simulacro;
[
  {
    "texto": "¿Cuál es la temperatura normal del cuerpo humano?",
    "opciones": [
      { "texto": "36-37 ºC", "correcta": true },
      { "texto": "38-39 ºC", "correcta": false },
      { "texto": "35 ºC", "correcta": false },
      { "texto": "40 ºC", "correcta": false }
    ]
  },
  {
    "texto": "¿Qué significa PWA?",
    "opciones": [
      { "texto": "Progressive Web App", "correcta": true },
      { "texto": "Public Web Access", "correcta": false },
      { "texto": "Private Web Application", "correcta": false },
      { "texto": "Programmed Web API", "correcta": false }
    ]
  }
]
import React from "react";
import Flashcard from "./components/Flashcard";
import Simulacro from "./components/Simulacro";
import preguntas from "./data/simulacro1.json";

function App() {
  return (
    <div className="App">
      <h1>TCAE SAS App</h1>
      <Flashcard pregunta="¿Qué es una PWA?" respuesta="Una Progressive Web App" />
      <Simulacro preguntas={preguntas} />
    </div>
  );
}

export default App;
