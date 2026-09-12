# ConCompas — Admin

Panel de administración de ConCompas, plataforma de intermediación de transporte en taxi para la provincia de Cádiz. Construido con Next.js (App Router) y Tailwind CSS.

## Desarrollo

```bash
cp .env.local.example .env.local
npm install
npm run dev
```

La app espera el backend (`concompas-backend`) corriendo en la URL indicada por `NEXT_PUBLIC_API_URL` (por defecto `http://localhost:3000`).

## Estructura

- `app/` — rutas y layouts (App Router)
- `services/` — clientes HTTP hacia el backend
- `types/` — tipos compartidos, alineados con los DTOs de respuesta del backend
