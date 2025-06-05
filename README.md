🎸 GuitarLA - React + TypeScript + Vite + useReducer 🛒

Proyecto de tienda de guitarras desarrollado con:

⚡ Vite para un entorno de desarrollo rápido y moderno.

⚛️ React con componentes funcionales.

📦 TypeScript para tipado estricto y mayor escalabilidad.

🧠 useReducer para una gestión de estado más robusta (ideal para carritos de compra).

💾 LocalStorage para persistir el carrito entre sesiones.

🔧 Funcionalidades

Visualización de guitarras con nombre, imagen, precio y descripción.

Agregar guitarras al carrito (con límite máximo por producto).

Incrementar o disminuir la cantidad de cada producto.

Eliminar productos del carrito individualmente.

Vaciar todo el carrito.

Carrito persistente en LocalStorage.

💡 Bonus
Código completamente tipado con types.ts para los modelos Guitar y CartItem.

Reducer centralizado (cartReducer.ts) para manejar todas las acciones del carrito con claridad y escalabilidad.

Diseño responsive y limpio (puedes añadir si usaste Bootstrap o Tailwind).

🗃️ Estructura básica
/src
  ├── components/
  ├── context/
  ├── data/
  ├── hooks/
  ├── types/
  └── App.tsx


🚀 Cómo correr el proyecto

npm install
npm run dev
