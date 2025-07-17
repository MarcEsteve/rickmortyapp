# 🧪 Rick & Morty React App

Una web app desarrollada con **React + TypeScript** que consume la API pública de Rick and Morty para mostrar personajes en una cuadrícula responsive. Cada personaje se presenta en una tarjeta con imagen, nombre y especie. Incluye paginación y filtrado por tipo.

## 🚀 Tecnologías utilizadas

- [React](https://react.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [Vite](https://vitejs.dev/)
- [Rick and Morty API](https://rickandmortyapi.com/)
- CSS Grid + Flexbox (estilos personalizados)

## 📦 Instalación

1. Clona el repositorio:

   ```bash
   git clone https://github.com/MarcEsteve/rickmortyapp.git
   cd rickmortyapi
   ```

2. Instala las dependencias:

   ```bash
   npm install
   ```

3. Inicia el entorno de desarrollo:

   ```bash
   npm run dev
   ```

## 🖥️ Funcionalidades

- ✅ Renderizado de 9 personajes en una cuadrícula de 3x3.
- ✅ Diseño responsive adaptado a dispositivos móviles.
- ✅ Filtro por tipos de personajes con botones interactivos.
- ✅ Uso de hooks personalizados (`useCharacters`) para gestionar peticiones a la API.
- ✅ Separación clara de estilos (`global.css` y `CharacterCard.css`).

## 📁 Estructura de carpetas

```
src/
├── components/
│   └── CharacterCard.tsx
├── hooks/
│   └── useCharacters.ts
├── styles/
│   ├── global.css
│   └── CharacterCard.css
├── App.tsx
├── main.tsx
```

## 🌐 API utilizada

- Endpoint principal: `https://rickandmortyapi.com/api/character`
- Documentación oficial: [Rick and Morty API Docs](https://rickandmortyapi.com/documentation)

## 📱 Capturas de pantalla

*(Puedes añadir aquí capturas del resultado en escritorio y móvil)*

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Puedes modificar y usar libremente este código con fines educativos o personales.

---

👨‍💻 Desarrollado por [Marc Esteve](https://github.com/MarcEsteve)
