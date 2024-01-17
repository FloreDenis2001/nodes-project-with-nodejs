# Web app for taking notes during courses/labs

## Goal

To develop a web app that allows students to take notes during courses/labs
 The thinking behind this is that note-taking requires effort. Rather than passively taking information in, the act of encoding the information into words or pictures forms new pathways in the brain, which stores it more firmly in long-term memory. On top of that, having the information stored in a new place gives students the opportunity to revisit it later and reinforce the learning that happened the first time around.
 
 
 # Instrucțiuni instalare, pornire și testare server

## Configurare backend

1. Pentru a clona codul sursă backend-ul:
```
git clone https://github.com/FloreDenis2001/notes-app-with-node
```
2. Pentru a clona codul sursă frontend-ul:
```
https://github.com/FloreDenis2001/notes-app-with-react-and-typescript
```

3. Instalează modulele npm pentru backend
```
npm install
npm install express
npm install --save sequelize
npm install --save mysql2
npm install --save cors
```
4. Execută scriptul server.js pentru a porni serverul.
```
node server.js
```

## Configurare frontend

2. Instalează modulele npm
```
npm install
npm install js-cookie  
npm install react-hook-form 
npm install react-router-dom 
npm install @types/react-router-dom @types/react-hook-form @types/js-cookie
npm install node-sass --save-dev
npm install @fortawesome/free-solid-svg-icons
npm install @fortawesome/react-fontawesome  
npm install antd  
npm install react-slick 
npm i --save-dev @types/react-slick 
```
3. Adăugați setările pentru mediu în fișierul .env
```
REACT_APP_API_BASEURL="http://127.0.0.1:3000"
REACT_APP_BASEURL="http://127.0.0.1:3001"
```
   ATENȚIE: Fără slash(/) la final.
## Pornire aplicație în mod dezvoltare

1. Navighează în directorul frontend și pornește aplicația de React
```
npm start 
```
Aplicația react va rula pe portul 3001, iar serverul pe portul 3000.


