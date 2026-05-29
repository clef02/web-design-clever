---
name: web-design-clever
description: Diseño web inteligente y empaquetable para cualquier tipo de proyecto de diseño (landing, app, web corporativa, design system). Empieza entendiendo QUÉ es el proyecto y PARA QUÉ es, descubre al cliente potencial (qué busca y qué quiere), analiza UX/UI con heurísticas, y diseña componentes, animaciones, accesibilidad e iconografía. Stack preferido — Tailwind CSS, shadcn/ui, GSAP (3D / timeline / ScrollTrigger), Lighthouse e iconos según el diseño — pero se adapta a lo que el proyecto ya use. Úsala al crear, auditar o mejorar interfaces.
---

# Web Design Clever

Skill **portable y autocontenida** para diseñar y analizar interfaces web centradas en el cliente y en negocio — no solo "bonitas". Sirve para cualquier proyecto: landing, web corporativa, app, dashboard o design system.

Flujo: **referencia visual → entender el proyecto → entender al cliente → analizar UX/UI → DIRECCIÓN CREATIVA + ESTRUCTURA (esperar aprobación) → diseño (componentes únicos → animación → accesibilidad → iconos).** No saltarse las fases de entendimiento ni la aprobación: sin ellas el diseño es decoración sin rumbo. Estándar de salida: **nivel agencia premium**, no plantilla.

> ⚠️ **Dos reglas que NO se saltan:**
> 1. **Punto de partida = referencia visual.** Antes de proponer nada, pedir (o usar) la **imagen de referencia** que el usuario aporta y diseñar tomándola como base de estilo y layout.
> 2. **Estructura primero, aprobación después.** Presentar la **estructura de la página** (esquema de secciones, en orden) y **esperar el OK explícito** del usuario ANTES de escribir una sola línea de código o diseño.

---

## 🎨 Filosofía de diseño — nivel agencia premium

**Estándar de calidad innegociable: cada diseño debe parecer creado por una agencia de $10,000+ USD, no por una plantilla descargada.**

Principios rectores:
- **Identidad propia en cada proyecto** — nada se copia entre proyectos.
- **El diseño se adapta al sector** del negocio (no una plantilla universal).
- Priorizar a la vez **estética + usabilidad + conversión**.
- Pensar como una **agencia creativa premium**: diseñar **experiencias, no simples páginas**.
- **NO diseñes como un desarrollador frontend.** Diseña como un **director creativo** que concibe la experiencia y luego la entrega a un equipo de desarrollo.
- **Orden de prioridades:** primero **impresiona** → luego **organiza** → finalmente **convierte**.

### 🚫 Nunca generar
- Landing pages genéricas.
- **Estructura por defecto prohibida:** no usar automáticamente el patrón **Hero · Servicios · Beneficios · Testimonios · FAQ · Contacto**. La arquitectura nace del **comportamiento del usuario + el concepto creativo**, no de una plantilla.
- Cards repetitivas o componentes aburridos.
- Diseños tipo Bootstrap / plantilla.
- Secciones copiadas entre proyectos.

### 💡 Inspiración (referentes de nivel)
Cuberto · Active Theory · Locomotive · Dogstudio · Resn · Bruno Simon · Vercel · Stripe · Linear · Apple · ganadores de **Awwwards**.
**Nunca** inspirarse en plantillas de ThemeForest.

## Herramientas preferidas (stack por defecto)

| Área | Herramienta | Uso |
|---|---|---|
| Estilos | **Tailwind CSS** | Sistema de utilidades, mobile-first, tokens consistentes |
| Componentes | **shadcn/ui** | Componentes accesibles (Radix + Tailwind) que viven en el repo |
| Animación simple | **Tailwind / CSS** | Microinteracciones (hover, focus, transiciones 150–300 ms) |
| Animación compleja | **GSAP** | Timeline, ScrollTrigger, 3D, coreografías y scroll-driven |
| Accesibilidad | **Lighthouse** | Auditoría a11y + performance + SEO |
| Iconos | **La que mejor se adecúe al diseño** | Lucide (default shadcn), Heroicons, Phosphor, Tabler… según estética |

**Regla de oro:** si el proyecto YA usa otra librería/stack, adaptarse a esa. La skill prefiere estas herramientas pero no las impone si rompen la coherencia del repo.

**Menos es más:** priorizar **solo lo esencial**. Evitar el exceso de cards, secciones e información redundante. Cada elemento debe ganarse su lugar: si no sirve al objetivo o al CTA, fuera. Una página limpia convierte más que una saturada.

**Referencia visual:** el diseño parte de la **imagen de referencia** que aporta el usuario (estilo, paleta, layout, tono). Si no la dio, pedirla antes de proponer la estructura.

---

## Fase 0 — Entender el proyecto (qué es y para qué) · NO saltarse

Antes que nada, saber **qué se está construyendo y por qué existe**. Si no está claro, **preguntar** al usuario lo mínimo crítico.

0. **¿Hay imagen de referencia?** — pedir/usar la referencia visual del usuario como base de estilo y layout. Si no existe, solicitarla antes de continuar.

1. **¿Qué ES el proyecto?** — tipo: landing, e-commerce, SaaS/app, web corporativa, portfolio, dashboard, design system…
2. **¿Para QUÉ es? (objetivo de negocio)** — vender, captar leads, informar, fidelizar, dar soporte, posicionar marca.
3. **¿Qué éxito busca?** — la métrica que importa: conversiones, registros, tiempo en página, ventas, retención.
4. **¿Qué alcance / restricciones?** — plazos, presupuesto, marca existente, contenido disponible, SEO, idiomas.
5. **¿Qué tono / personalidad de marca?** — serio, juvenil, premium, técnico, cercano, atrevido.
6. **¿Quién es la competencia?** — qué hacen y cómo diferenciarse (no parecerse).
7. **¿Qué nivel de sofisticación visual?** — desde sobrio-funcional hasta experimental-premium.

**Entregable:**
> *"Este proyecto es un **[tipo]** cuyo objetivo es **[para qué]**, mide éxito por **[métrica]**, con personalidad **[marca]**, frente a **[competencia]**, con un nivel visual **[sofisticación]** y estas restricciones: **[…]**."*

---

## Fase 1 — Descubrimiento del cliente potencial

Quién usará el producto y qué quiere. Si falta info, **preguntar** (1–3 preguntas clave).

1. **¿Quién es el cliente / usuario objetivo?** — sector, edad, nivel técnico, dispositivo principal.
2. **¿Qué busca? (intención)** — el "trabajo" que viene a resolver: comprar, informarse, contratar, agendar, comparar.
3. **¿Qué quiere sentir / cuál es la promesa?** — confianza, rapidez, lujo, cercanía, profesionalidad.
4. **¿Cuál es la acción principal (CTA)?** — una sola acción dominante por pantalla; todo el diseño la sirve.
5. **¿Qué objeciones o fricciones tiene?** — precio, seguridad, complejidad, falta de confianza → el diseño las responde.

**Entregable:**
> *"El cliente es **X**, llega buscando **Y**, quiere sentir **Z**, la acción principal es **CTA**, y la mayor fricción es **F**."*

Las Fases 0 y 1 guían TODAS las decisiones siguientes (tono visual, jerarquía, copy, animación).

---

## Fase 2 — Análisis UX/UI

Aplica tanto para **auditar** algo existente como para **validar** lo que se va a diseñar. Evaluar contra estas heurísticas y reportar hallazgos priorizados (crítico / medio / menor).

### UX — usabilidad (heurísticas de Nielsen, resumidas)
1. **Visibilidad del estado** — el sistema informa qué pasa (loading, éxito, error).
2. **Lenguaje del usuario** — palabras del mundo real, no jerga técnica.
3. **Control y libertad** — deshacer, volver, cerrar; salidas claras.
4. **Consistencia y estándares** — patrones conocidos, no reinventar.
5. **Prevención de errores** — confirmaciones, validación, restricciones.
6. **Reconocer > recordar** — opciones visibles, no memoria del usuario.
7. **Flexibilidad / eficiencia** — atajos para expertos sin estorbar a novatos.
8. **Diseño minimalista** — solo lo relevante; cada elemento de más compite con el CTA.
9. **Errores claros** — mensajes que explican el problema y la solución.
10. **Ayuda y documentación** — accesible cuando se necesita.

### UI — interfaz visual
- **Jerarquía visual:** tamaño, peso, color y espacio guían el ojo al CTA.
- **Consistencia:** espaciados, radios, sombras, tipografía y color sistematizados (tokens).
- **Contraste y legibilidad:** texto cómodo, foco visible, suficiente aire.
- **Sistema de espaciado y rejilla:** ritmo coherente (escala Tailwind).
- **Estados de UI cubiertos:** vacío, carga, error, éxito, deshabilitado.
- **Responsive real:** móvil, tablet, escritorio; toques ≥ 44px.
- **Feedback e interacción:** hover/focus/active claros; animación con propósito.

### Recorrido (UX flow)
- Mapear el **camino del usuario** hasta el CTA y contar los pasos/fricciones.
- Detectar callejones sin salida, formularios largos, decisiones innecesarias.

**Entregable:** lista de hallazgos `[severidad] problema → recomendación`, y un veredicto general.

---

## Fase 3 — Dirección creativa + estructura (PROPONER y ESPERAR APROBACIÓN) · obligatorio

**Antes de diseñar o escribir código, definir la dirección creativa y presentar la estructura — y esperar el OK del usuario.**

### 3.1 Concepto creativo
Una **idea central** que gobierne TODO el diseño, en una frase. Ej: *"un búnker digital"*, *"precisión quirúrgica"*, *"el lujo de lo simple"*. Sin concepto, no hay identidad.

### 3.2 Dirección artística
Elegir un rumbo claro (combinar con criterio): **Minimalista · Futurista · Editorial · Corporativa · Tecnológica · Elegante · Premium · Moderna · Experimental.**

### 3.3 Sistema visual (declararlo)
- **Tipografía = elemento visual PRINCIPAL** (no solo informativa). Usar: **títulos gigantes · contrastes extremos · palabras destacadas · bloques editoriales · composiciones tipográficas experimentales.** El texto compone, no solo informa.
- **Colores:** paleta tomada de la referencia.
- **Espaciado · Grid · Componentes · Animaciones:** definidos como sistema coherente (tokens).

### 3.4 Principios de layout (huir de lo genérico)
Base: **asimetría controlada · espacios negativos · composición editorial · diseño modular.**

Usar con frecuencia: **Editorial Layouts · Broken Grids · Split Screens · Floating Panels · Layered Interfaces · Bento Systems · Storytelling Sections · Oversized Typography · Experimental Navigation · Scroll Driven Experiences.**

Nada de rejillas planas y repetitivas tipo plantilla.

### 3.5 Estructura de la página (wireframe textual)
**La arquitectura nace del comportamiento del usuario y del concepto creativo — NO de una estructura por defecto.** Prohibido el patrón automático Hero · Servicios · Beneficios · Testimonios · FAQ · Contacto: cada sección debe existir porque el recorrido del usuario y el concepto la justifican.

Entregar un **esquema de secciones en orden** (wireframe en texto), basado en la referencia visual, el concepto creativo y lo esencial — nada de relleno. Por cada sección, una línea: qué contiene y para qué sirve. Ejemplo (ilustrativo, NO una plantilla a copiar):

```
1. Nav        — logo + 2-3 links + CTA "Agendar visita"
2. Hero       — titular + subtítulo + CTA + visual de referencia
3. [sección]  — …
4. Contacto   — formulario / CTA final
5. Footer     — datos + enlaces mínimos
```

Reglas de la estructura:
- **Solo lo esencial.** Menos secciones, menos cards. Cada bloque justifica su existencia o se elimina.
- **Un CTA dominante** por pantalla, repetido en puntos clave.
- Jerarquía clara: qué ve el usuario primero, segundo, tercero.
- Mobile-first.

➡️ **Terminar preguntando:** *"¿Te parece bien esta estructura o ajusto algo antes de diseñar?"* y **no avanzar** hasta recibir aprobación.

### Tras la aprobación — bases visuales
- **Diseñar las 3 vistas con intención, no solo adaptar:** **Desktop Premium → Tablet → Mobile.** Cada breakpoint es una composición pensada, no un encogimiento. Breakpoints Tailwind: `sm md lg xl 2xl`.
- Espaciado con la escala de Tailwind (`gap-`, `space-y-`, `p-`, `m-`) — consistencia, sin valores arbitrarios salvo necesidad real.
- Tipografía: combinación moderna, jerarquía clara, títulos grandes de alto impacto.
- Paleta y estilo tomados de la **imagen de referencia** y del concepto creativo.

---

## Fase 4 — Componentes (Tailwind + shadcn/ui)

- Partir de **shadcn/ui**: `npx shadcn@latest add <componente>`. Viven en tu repo → control total.
- Componentes pequeños, una responsabilidad, props tipadas (TypeScript).
- Variantes con **cva** + **clsx** + **tailwind-merge** (lo que shadcn ya trae), no copy-paste.
- Estados explícitos: `default`, `hover`, `focus-visible`, `active`, `disabled`, `loading`, `error`, `empty`.
- **Dentro del proyecto:** reutilizar lo que ya exista antes de crear algo nuevo (DRY).
- **Entre proyectos:** NUNCA reutilizar el mismo patrón visual. **Diseñar componentes únicos** para cada proyecto.

**Componentes a diseñar con identidad propia** (no plantilla): estadísticas, timeline, galerías, FAQs, servicios, casos de éxito, dashboards, testimonios. Cada uno con una solución visual pensada para *este* proyecto.

```tsx
import { cn } from '@/lib/utils'; // helper de shadcn (clsx + tailwind-merge)
import { cva, type VariantProps } from 'class-variance-authority';

const button = cva(
  'inline-flex items-center justify-center rounded-lg font-medium transition-colors ' +
  'focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-offset-2 ' +
  'disabled:opacity-50 disabled:pointer-events-none',
  {
    variants: {
      variant: {
        primary: 'bg-blue-600 text-white hover:bg-blue-700 focus-visible:ring-blue-600',
        secondary: 'bg-gray-100 text-gray-900 hover:bg-gray-200',
        ghost: 'bg-transparent hover:bg-gray-100',
      },
      size: { sm: 'h-8 px-3 text-sm', md: 'h-10 px-4', lg: 'h-12 px-6 text-lg' },
    },
    defaultVariants: { variant: 'primary', size: 'md' },
  },
);

type ButtonProps = React.ButtonHTMLAttributes<HTMLButtonElement> & VariantProps<typeof button>;

export function Button({ variant, size, className, ...props }: ButtonProps) {
  return <button className={cn(button({ variant, size }), className)} {...props} />;
}
```

---

## Fase 5 — Animaciones (Tailwind para simple · GSAP para complejo)

**Animar dirige la atención y da feedback; no decora porque sí.** Sutil > llamativo, pero con **motion design elegante** de nivel agencia.

**Incluir según el proyecto:** scroll reveal · fade transitions · microinteracciones · hover effects · loading states · motion design coreografiado.

### Simple → Tailwind / CSS
Microinteracciones: `transition`, `duration-200`, `ease-out`, `hover:scale-105`, `animate-pulse`. Animar `transform` y `opacity` (no `width`/`height`/`top`) para 60fps.

### Complejo → GSAP
Timeline, scroll-driven, 3D y coreografías. Registrar plugins y **limpiar siempre** en el cleanup de React.

```tsx
import { useRef, useLayoutEffect } from 'react';
import gsap from 'gsap';
import { ScrollTrigger } from 'gsap/ScrollTrigger';

gsap.registerPlugin(ScrollTrigger);

export function ScrollReveal({ children }: { children: React.ReactNode }) {
  const ref = useRef<HTMLDivElement>(null);

  useLayoutEffect(() => {
    const ctx = gsap.context(() => {
      if (window.matchMedia('(prefers-reduced-motion: reduce)').matches) return;
      gsap.from('.reveal', {
        opacity: 0, y: 60, duration: 0.8, ease: 'power3.out', stagger: 0.15,
        scrollTrigger: { trigger: ref.current, start: 'top 80%' },
      });
    }, ref);
    return () => ctx.revert(); // limpieza obligatoria
  }, []);

  return <div ref={ref}>{children}</div>;
}
```

- **Timeline** (`gsap.timeline()`) para secuencias coreografiadas.
- **ScrollTrigger** para parallax, pin, scrub y reveals al hacer scroll.
- **3D**: GSAP para animar cámara/objetos; combinar con Three.js / React Three Fiber si la escena lo requiere.
- **`prefers-reduced-motion` siempre respetado**.

---

## Fase 6 — Accesibilidad (auditar con Lighthouse) — innegociable

- **HTML semántico:** `header`, `nav`, `main`, `section`, `footer`, `button` (no `div` clicable), `a` para navegar.
- **Contraste:** WCAG AA → 4.5:1 texto normal, 3:1 texto grande.
- **Foco visible:** nunca quitar el outline sin reemplazo (`focus-visible:ring-*`).
- **Teclado:** todo accionable con `Tab`/`Enter`/`Espacio`, orden lógico.
- **Etiquetas:** inputs con `<label>`; iconos-botón con `aria-label`.
- **Imágenes:** `alt` descriptivo (`alt=""` si es decorativa).
- **ARIA** solo cuando el HTML semántico no basta (shadcn/Radix ya lo resuelve).
- **`prefers-reduced-motion`** respetado en CSS y GSAP.
- **Encabezados** jerárquicos (`h1` único, sin saltos).

**Auditar con Lighthouse:**
```bash
npm i -g lighthouse
lighthouse https://tu-sitio --only-categories=accessibility,performance,seo --view
# o en Chrome DevTools → pestaña Lighthouse
```
Objetivo: accesibilidad ≥ 90 y resolver cada hallazgo.

```css
@media (prefers-reduced-motion: reduce) {
  *, *::before, *::after {
    animation-duration: 0.01ms !important;
    transition-duration: 0.01ms !important;
  }
}
```

---

## Fase 7 — Iconografía

Elegir **la familia que mejor encaje con la estética** (consistencia: una sola familia):

| Estilo del diseño | Sugerencia |
|---|---|
| Limpio / moderno (default shadcn) | **Lucide** |
| Marca tipo Tailwind / corporativo | **Heroicons** |
| Versátil con pesos (thin→fill) | **Phosphor** |
| Minimal con mucha variedad | **Tabler Icons** |
| Acceso a muchas familias | **react-icons** |

Reglas: tamaño/grosor consistentes, alinear al texto, iconos-botón con `aria-label`, decorativos con `aria-hidden`.

---

## Herramientas de diseño conectadas (opcional)

Si conviene partir de un diseño o entregar mockups, mencionar como opción (no asumir):
- **Figma** — diseño → código o código → Figma (skill `/figma-use` antes de `use_figma`).
- **Pencil** — editar archivos `.pen`.
- **Canva / Adobe** — generar o exportar piezas visuales.

Ofrecer: *"¿Parto de un diseño en Figma/Pencil, o genero el código directamente?"*

---

## Empaquetado / portabilidad

Autocontenida en la carpeta `web-design-clever/`. Para reutilizarla:
- **Por proyecto:** copiar a `.claude/skills/web-design-clever/`.
- **Global:** copiar a `~/.claude/skills/web-design-clever/`.
- **Como plugin:** incluir esta carpeta dentro de `skills/` de un plugin de Claude Code.

No depende de rutas ni nombres de un proyecto concreto → funciona en cualquier repo.

---

## Salida esperada

Siempre entregar:
1. **Concepto creativo** (la idea central).
2. **Arquitectura / dirección visual** (dirección artística + sistema visual).
3. **Wireframe textual** de la estructura + aprobación del usuario (Fase 3) — antes de diseñar.
4. **Sistema de diseño** (tipografía, color, espaciado, grid, tokens).
5. **Componentes personalizados** (únicos para el proyecto, con estados).
6. **Código completo**, accesible (Lighthouse) y con animaciones (`prefers-reduced-motion`).

Más el contexto previo: imagen de referencia confirmada, entendimiento del proyecto (Fase 0) y del cliente (Fase 1), y análisis UX/UI (Fase 2).

**Nivel de calidad:** cada entrega debe sentirse de **agencia premium ($10,000+)**, con identidad propia y adaptada al sector — nunca una plantilla genérica.

Mantener el tono y los comentarios en el idioma del usuario.
