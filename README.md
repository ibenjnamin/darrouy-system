# DARROUY - Sitio Corporativo Profesional

Landing corporativa desarrollada con Astro.

## Objetivo

Este sitio NO está planteado como portafolio personal.
Presenta DARROUY como empresa de desarrollo tecnológico, software,
desarrollo web, integraciones, automatización y soluciones digitales.

## Levantar proyecto

1. Descomprime el ZIP.
2. Abre la carpeta en VS Code.
3. Abre una terminal en la raíz.
4. Ejecuta:

```bash
npm install
```

Luego:

```bash
npm run dev
```

Abre la URL que entregue Astro, normalmente:

```text
http://localhost:4321/
```

## Logo

Copia tu logo en:

```text
public/logo.png
```

## Contacto

Edita:

```text
src/components/Contact.astro
```

Reemplaza:

```text
i.benjaminbd@gmail.com
569XXXXXXXX
```

## Estructura

```text
src/
├── components/
│   ├── Header.astro
│   ├── Hero.astro
│   ├── Company.astro
│   ├── Services.astro
│   ├── Capabilities.astro
│   ├── Process.astro
│   ├── Contact.astro
│   └── Footer.astro
├── layouts/
│   └── BaseLayout.astro
├── pages/
│   └── index.astro
└── styles/
    └── global.css
```

## Producción

```bash
npm run build
```

Para probar la build:

```bash
npm run preview
```


## Cambios V2

- Correo configurado: i.benjaminbd@gmail.com
- Botón de correo actualizado con asunto y mensaje inicial.
- Fondo con más profundidad, luces y movimiento suave.
- Tarjetas con hover, elevación y brillo sutil.


## Contacto V3

El formulario de correo ya NO utiliza `mailto:`.

Envía mediante FormSubmit directamente a:

```text
i.benjaminbd@gmail.com
```

La primera vez debes enviar una prueba y confirmar el mensaje de activación
que llegará a ese Gmail.

Para WhatsApp, edita `src/components/Contact.astro` y reemplaza:

```text
569XXXXXXXX
```

por el número real de DARROUY.


## Contacto V4 - AJAX

El formulario ahora se envía sin redirecciones usando AJAX.

Al enviarse correctamente aparece un aviso flotante abajo a la derecha:

`Correo enviado con éxito`

Destino:

`i.benjaminbd@gmail.com`

FormSubmit requiere una activación inicial del correo receptor. Una vez activado,
los visitantes permanecen siempre dentro de la web durante el envío.


## V5 - Fondo animado

Se mantuvo la misma estructura y funcionalidad de la V4.

Cambios visuales:
- Luces azules y celestes con movimiento muy suave.
- Partículas/puntos tecnológicos con baja opacidad.
- Movimiento ambiental lento para dar más vida sin recargar.
- Compatibilidad con `prefers-reduced-motion`.
