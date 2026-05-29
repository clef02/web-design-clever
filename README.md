# Web Design Clever 🎨

Plugin de [Claude Code](https://claude.com/claude-code) con una skill de **diseño web inteligente** para cualquier tipo de proyecto: landing, web corporativa, app, dashboard o design system.

No diseña "bonito" porque sí: primero entiende **qué es el proyecto y para qué**, descubre al **cliente potencial** (qué busca y qué quiere), **analiza UX/UI** con heurísticas, y recién entonces diseña.

## ✨ Qué hace

Sigue un flujo en fases:

1. **Entender el proyecto** — qué es y para qué (objetivo de negocio, métrica de éxito, alcance, tono de marca).
2. **Cliente potencial** — quién es, qué busca, qué quiere sentir, CTA, fricciones.
3. **Análisis UX/UI** — heurísticas de Nielsen + auditoría visual + recorrido del usuario, con hallazgos priorizados.
4. **Estructura y jerarquía** — mobile-first, CTA dominante.
5. **Componentes** — Tailwind + shadcn/ui, accesibles, con todos los estados.
6. **Animaciones** — Tailwind para microinteracciones, GSAP para timeline / ScrollTrigger / 3D.
7. **Accesibilidad** — checklist WCAG, auditable con Lighthouse.
8. **Iconografía** — la familia que mejor encaje con la estética.

## 🧰 Stack preferido

| Área | Herramienta |
|---|---|
| Estilos | Tailwind CSS |
| Componentes | shadcn/ui |
| Animación compleja | GSAP (ScrollTrigger, Timeline, 3D) |
| Accesibilidad | Lighthouse |
| Iconos | Lucide / Heroicons / Phosphor / Tabler (según diseño) |

> Si tu proyecto ya usa otro stack, la skill se adapta a lo que tengas.

## 📦 Instalación

### Como plugin (marketplace)

```bash
# En Claude Code
/plugin marketplace add clef02/web-design-clever
/plugin install web-design-clever
```

### Manual (copiar la skill)

Copia la carpeta de la skill a tu proyecto o a tu config global:

```bash
# Por proyecto
cp -r skills/web-design-clever .claude/skills/

# Global (todos tus proyectos)
cp -r skills/web-design-clever ~/.claude/skills/
```

## 🚀 Uso

En Claude Code:

```
/web-design-clever
```

Luego cuéntale qué quieres diseñar o auditar. Si falta contexto (qué es el proyecto, quién es el cliente), te lo preguntará antes de empezar.

## 📄 Licencia

MIT © clef02
