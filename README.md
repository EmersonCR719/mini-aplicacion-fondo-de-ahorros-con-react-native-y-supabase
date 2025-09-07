# Mini Proyecto con Supabase

Este proyecto es un ejercicio simple para practicar la conexión entre un proyecto JavaScript y una base de datos gestionada en **Supabase**.  

## 🛠 Tecnologías utilizadas
- JavaScript (ES Modules)
- React Native
- Expo
- [Supabase](https://supabase.com/) como backend (Base de datos y API)

## 📂 Estructura del proyecto
bd-app/
├── assets/            # Imágenes y otros recursos
├── node_modules/      # Dependencias del proyecto
├── screens/           # Pantallas de la aplicación
│   ├── MisAhorros.js      # Pantalla con los ahorros del usuario
│   └── TodosAhorros.js    # Pantalla con todos los ahorros
├── supabase.js        # Configuración de conexión a Supabase
├── App.js             # Punto de entrada principal de la app
├── app.json           # Configuración de Expo
├── index.js           # Registro de la app
├── package.json       # Dependencias y scripts
└── .gitignore         # Archivos y carpetas ignoradas por git

## 🚀 Configuración
1. **Clonar el repositorio**
   ```bash
   git clone https://github.com/<tu-usuario>/<nombre-del-repo>.git
   cd <nombre-del-repo>
3. **Instalar dependencias**
   npm install
2. **Configurar Supabase en supabase.js**
   import { createClient } from '@supabase/supabase-js';
   const supabaseUrl = 'https://<TU-PROYECTO>.supabase.co';
   const supabaseAnonKey = '<TU_ANON_KEY>';
  
   export const supabase = createClient(supabaseUrl, supabaseAnonKey);
3. **Ejecutar el proyecto con Expo**
   npx expo start


