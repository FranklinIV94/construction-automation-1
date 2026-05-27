# Construction Automation Platform

A project management and 3D visualization platform for construction and interior design firms. Supports the full project lifecycle with role-based access, 3D model hosting, and client review workflows.

**Deployed for construction and design firms in Florida. Customizable for any market.**

## Features

- **Project Management** — Create, edit, delete projects with status tracking and milestone management
- **3D Model Hosting** — Upload and display `.glb`/`.gltf` files per project with real-time 3D rendering
- **Role-Based Access** — ADMIN (upload/manage) and CLIENT (view only) roles
- **Client Review Workflows** — Share 3D models with clients for review and approval
- **Secure Authentication** — NextAuth v4 + Supabase credentials-based auth

## Tech Stack

- **Frontend:** Next.js 15 (App Router) + TypeScript
- **3D Rendering:** React Three Fiber + Drei (GLTF model loader)
- **Auth:** NextAuth v4
- **Database + Storage:** Supabase (PostgreSQL + Storage)
- **Deployment:** Vercel

## Architecture

```
Client Browser → Vercel (Next.js SSR) → Supabase (DB + Storage)
                                     → R3F (WebGL 3D rendering)
```

## Deployment & Customization

This platform can be deployed and customized for any construction or interior design firm in 1-3 weeks:

- Custom project stages and milestone workflows
- Branding (logo, colors, domain)
- Additional file format support (DWG, IFC, OBJ)
- Integration with project management tools (Procore, PlanGrid)
- Custom client presentation modes

**Contact [ALBS](https://simplifyingbusinesses.com) for deployment and customization.**

## License

Proprietary. Source available for review. Deployment and commercial use requires a license from All Lines Business Solutions.