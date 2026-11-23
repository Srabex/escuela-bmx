# Escuela BMX (nombre por definir)

Escuela presencial de BMX Race en Chihuahua. Proyecto con Jorge Acosta; Sebas lleva administración, programa y plataforma. **Independiente de BMX Mentors (plataforma de Nacho Cattana): no mezclar.** Nacho solo aparece como invitado ocasional a clínicas (sin nombre en el sitio por ahora).

## Estado (23 nov 2026)

- Cascarón de landing en `public/index.html` (HTML/CSS/JS estático, sin compilación; modelo Luigi's Clean). Todo lo que falta está marcado con `<span class="pend">Pendiente</span>` y hay una lista de pendientes al final de la página. Banner de "Borrador interno" arriba y `noindex`: quitar ambos al publicar.
- Publicado de prueba en el Worker `escuela-bmx`: https://escuela-bmx.srab17-6.workers.dev (build vacío, deploy `npx wrangler deploy`, producción en `main`). Sin dominio todavía.

## Datos confirmados

- Sedes: pista **La Cantera** (Parque Extremo La Cantera) y **ciclopista de la Ciudad Deportiva**. Bowl: lugar pendiente.
- Horario: martes y jueves 6:00 pm pista; miércoles 6:00 pm ciclopista; sábado 9:00 am bowl. Semillero martes y jueves (hora pendiente).
- Edades: Semillero de 3–4 a 6 años con bici de balance (strider); de 6 en adelante, ya con pedales, entrenan con los demás. Después del Semillero hay 2 niveles: Nivel 1 = principiante e intermedio; Nivel 2 = experto.
- Precios tentativos: Semillero $1,200/mes; demás $1,000/mes. Inscripción y clase muestra pendientes.
- Entrenador principal: **Fabián** (corredor de BMX). Auxiliares sin nombre todavía (Carlos Luis Mateo no ha confirmado: no ponerlo).
- Ya tienen sensores y ProGate.
- Gimnasio, nutriólogo y psicólogo deportivo: ideas de Jorge, sin convenio todavía (marcados como pendiente).
- WhatsApp de prueba: el de Sebas, 614 235 5166 (`WA` en el script). Mensajes empiezan "Hola, vengo de la página de la escuela de BMX." Cambiar a "vengo de <dominio>" cuando haya dominio.

## Tono y mensaje

- Diferenciador: **metodología**. Entrena un corredor que ha sentido la bici (no solo condición física y fuerza) y enseña con tacto y paciencia para que los niños quieran seguir.
- No pelear con nadie ni prometer de más: no decir "la primera" ni "la única", no nombrar a otras escuelas.
- Nombre: no usar "Dorados de Chihuahua" (marca de los equipos profesionales).
- Formulario de inscripción sin fecha de nacimiento ni datos médicos (menores; eso se ve en persona).

## Antes de publicar (estándar `claude/estandar-sitios.md`)

- Nombre, logo y colores; OG 1200×630 con foto real (`diseno/og.html` → `public/og.jpg`); favicon .ico/.png, apple-touch-icon, icon-192/512, `site.webmanifest`; datos estructurados `SportsActivityLocation`; quitar banner y `noindex`; robots y sitemap.
- Cloudflare: Import a repository → `Srabex/escuela-bmx`, build vacío, deploy `npx wrangler deploy`.
