# Auditoría de GitHub — Wafer2000

**Objetivo:** Que la presencia pública respalde «Senior Software Engineer · Mobile · Backend · Cloud · Applied AI» sin publicar código ni información confidencial.

**Alcance:** Revisión de metadatos y archivos de configuración, READMEs, estructuras, scripts y directorios de pruebas. **No se ejecutaron los proyectos ni se realizó una auditoría integral de seguridad, arquitectura o cobertura.**

## Inventario de los 14 repositorios privados

| Repositorio | Evidencia observada | Decisión | Publicación recomendada |
|---|---|---|---|
| `apple-device-inventory` | Next.js 16, TypeScript, Supabase, crédito, ventas, inventario, scripts de pruebas | ⭐ Prioridad 1 | Caso público saneado; **código completo privado** |
| `MusicLinks` | Python, PowerShell, C#, Supabase Edge Functions, licenciamiento y tests | ⭐ Prioridad 2 | Caso público saneado; **código completo privado** |
| `random_playlist` | Next.js 15, OAuth, varias APIs musicales, Supabase, pagos/sesiones | ⭐ Prioridad 3 | Caso público saneado; código completo privado |
| `ai_global` | Flutter, Firebase/Cloud Functions, integraciones, tests, GitHub Actions en `develop` | ⭐ Prioridad 4 | Caso público saneado; mantener código privado |
| `la-raya-container-registry` | Next.js, Supabase, RLS, PWA/offline, IndexedDB, Jest | ⭐ Prioridad 5 | Caso **genérico y anónimo** sujeto a permiso del propietario |
| `ruta_cero` | Flutter, Riverpod, Drift, Supabase, lógica financiera, offline-first | ⭐ Prioridad 6 | Caso público; evaluar demo de código propio tras saneamiento |
| `ai-global-web` | Next.js 16, Supabase, auditorías de seguridad/i18n, comercio y academia | Alternativa Full-Stack | Caso público sin código comercial |
| `newyorkrents_app` | Flutter, BLoC, Clean Architecture, Shopify GraphQL | Alternativa Mobile | Caso público; código solo con autorización y rotación del token |
| `rally_iq` | Garmin Connect IQ; hay un archivo `developer_key.der` | Mantener privado | Solo presentación técnica sin llave ni binarios de firma |
| `rica-sazon` | Next.js, Supabase, pedidos y administración | Mantener privado | Caso opcional con permiso del cliente |
| `ip-global-digital` | Firebase/web, `.env.local` con ajustes de Cloudinary | Mantener privado | No publicarlo sin revisar acceso, activos y derechos |
| `pyme_master` | Flutter/Firebase; README inicial genérico | Mejorar documentación | No destacarlo de momento |
| `ai` | Flutter inicial, sin evidencia documentada de sistema de IA | Mantener privado | No presentarlo como AI Engineering |
| `mario-portfolio` | Next.js, contenido bilingüe, pnpm, Vercel | Opcional | Se podría abrir con permiso y revisión de assets/datos |

### Notas para evitar afirmaciones incorrectas

- `ai_global` y `ai-global-web` son nombres de producto; no demuestran por sí solos entrenamiento ni despliegue de modelos de IA.
- En `ai_global`, el código principal y el workflow de CI se observaron en `develop`, mientras que `main` estaba mayormente orientada a documentación. La rama que se presente debe aclararse.
- La existencia de scripts/tests no demuestra que estén pasando hoy; requeriría ejecutar la suite y verificar CI.
- Para trabajos de clientes/organizaciones, solo publicar materiales con autorización del titular y sin datos reales.

## Estrategia de publicación y pinned

### Fase de lanzamiento (sin exponer código privado)

Publicar el README del perfil y preparar 6 estudios de caso en inglés. Pueden vincularse al portafolio. No fijar seis repositorios vacíos o puramente decorativos: agregar diagramas útiles, contexto técnico, capturas anonimizadas y, cuando sea viable, ejemplos de código propios y saneados.

### Los seis candidatos finales a destacados

1. **Commerce & Credit Platform** — Full-Stack, Next.js, lógica de negocio, calidad.
2. **MusicLinks Licensing & Integrations** — Backend, licenciamiento, APIs, Python.
3. **Multi-Provider Playlist Platform** — OAuth, API Integration, SaaS.
4. **Cloud-Connected Digital Marketplace** — Flutter, Firebase, Cloud Functions, CI/CD.
5. **Container Operations PWA** — Next.js, RLS, offline, pruebas (solo con permiso).
6. **Ruta Cero** — Flutter, arquitectura de dominio, offline-first.

**Sustitución futura:** Reemplazar el candidato menos relevante por un repositorio **AI Cloud Platform** con código público real y pruebas cuando esté construido.

**Importante:** Los perfiles públicos no pueden demostrar el código de repositorios privados mediante pines; primero deben existir repositorios o demos visibles públicamente. GitHub permite fijar hasta seis repositorios/gists en el perfil.

## Qué debe contener cada repositorio público

- README en inglés que explique problema, decisiones de arquitectura, stack y límites de confidencialidad.
- Diagrama de arquitectura legible.
- Capturas con datos sintéticos (nunca clientes, licencias o registros reales).
- Si contiene código público: instrucciones reproducibles, `.env.example`, tests y build/lint verificables.
- Topics adecuados (ej.: `typescript`, `nextjs`, `supabase`, `flutter`, `cloud-engineering`, `api-integration`).
- No incluir métricas inventadas, logotipos/clientes sin permiso, código propietario, material de firma ni credenciales.

## Orden de ejecución

1. Resolver primero credenciales expuestas y auditar historial.
2. Crear repositorio público `Wafer2000/Wafer2000` con README del perfil.
3. Subir las fichas preparadas en `showcases/` como proyectos de presentación cuando exista autorización de publicación.
4. Anexar capturas anonimizadas o demos independientes.
5. Fijar los seis repositorios públicos desde «Customize your pins».
6. Actualizar enlaces desde portafolio y LinkedIn si tiene sentido.
7. Evaluar y priorizar un proyecto público AI Cloud real.

## Cambios ya ejecutados mediante la conexión de GitHub

- `Wafer2000/my_pm`: se retiró del HEAD el `.env` rastreado, se añadió un `.env.example` y reglas de `.gitignore`. **El token antiguo sigue potencialmente accesible en el historial y debe revocarse/rotarse.**
- `Wafer2000/newyorkrents_app`: el README actual sustituyó dos apariciones de una credencial Shopify Storefront por un placeholder. **Si el token es válido, rotarlo/revocarlo.**

No se ha hecho público ningún repositorio privado, no se han modificado políticas de acceso, no se han archivado repositorios y no se han cambiado los pines.
