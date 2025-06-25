Este proyecto es un dashboard interactivo hecho en React para visualizar indicadores y estadísticas de residuos recibidos por un relleno sanitario.

## Características
- Filtros por cliente y mes.
- Indicadores visuales:
  - Toneladas recibidas
  - Ingreso total
  - Duración promedio
  - Tiradas promedio por cliente
  - Kg promedio por entrega
  - Top 3 tipos de residuo
  - Top 3 clientes

## Requisitos
- Node.js (v18 o superior recomendado)
- npm

## Instalación
1. Clona este repositorio:
   ```
   git clone https://github.com/Sergiophysics/Prueba-RellenoSanitario.git
   cd Prueba-RellenoSanitario
   ```
2. Instala las dependencias:
   ```
   npm install
   ```

## Ejecución
Inicia el servidor de desarrollo:
```
npm run dev
```
Abre tu navegador en la URL que te indique la terminal (normalmente http://localhost:5173).

## Notas
- No subas la carpeta `node_modules` ni archivos `.env` con datos sensibles.
- Si necesitas variables de entorno, crea un archivo `.env.example` con el formato necesario.
- El archivo principal del dashboard es `src/App.jsx` o `src/Relleno sanitario.jsx` según tu estructura.
