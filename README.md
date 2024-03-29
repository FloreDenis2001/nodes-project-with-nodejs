# Web app for taking notes during courses/labs

## Goal

Pentru a dezvolta o aplicație web care să le permită studenților să ia notițe în timpul cursurilor și laboratoarelor, trebuie să ne concentrăm pe faptul că actul de a lua notițe necesită un efort conștient. Procesul de notare nu este doar o simplă înregistrare pasivă a informațiilor; el implică transformarea și codificarea acestora în cuvinte sau imagini, ceea ce creează noi căi neuronale în creier. Aceasta contribuie la consolidarea informațiilor în memoria pe termen lung.

Mai mult decât atât, stocarea informațiilor într-un mediu nou oferă studenților șansa de a se întoarce la acestea mai târziu, consolidând astfel învățarea care a avut loc inițial. Astfel, aplicația noastră web nu va fi doar un simplu instrument de notare, ci un facilitator al procesului de învățare și memorare, oferind studenților posibilitatea de a-și organiza și revizui materialele de curs într-un mod eficient și interactiv.
 
 
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


