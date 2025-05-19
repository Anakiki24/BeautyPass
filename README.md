# BeautyPass
BeautyPass

## Estructura del proyecto
BeautyPass/ # Nombre del proyecto
├── App/ # Aplicación móvil (React Native)
│ ├── src/
│ │ ├── components/
│ │ ├── screens/
│ │ ├── navigation/
│ │ ├── store/ # (Si usas Redux o Zustand)
│ │ ├── services/
│ │ ├── assets/
│ │ ├── App.js
│ │ └── index.js
│ ├── app.json
│ └── package.json
├── Admin/ # Panel administrativo (Next.js)
│ ├── pages/
│ │ ├── api/ # (Si tienes API routes en Next.js)
│ ├── components/
│ ├── public/
│ ├── styles/
│ ├── utils/
│ ├── context/ # (Si usas Context API)
│ └── package.json
├── Backend/ # Backend (Node.js)
│ ├── controllers/
│ ├── routes/
│ ├── models/
│ ├── config/
│ ├── middleware/
│ ├── utils/
│ ├── services/ # (Opcional)
│ ├── app.js # (O index.js si usas Express puro)
│ └── package.json
├── docs/ # Documentación
│ ├── manual-usuario.md
│ ├── manual-operaciones.md
│ └── manual-mantenimiento.md
└── README.md # Descripción general del proyecto
