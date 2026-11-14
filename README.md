# Cotizador Popurrí Estudio

Calculadora de cotizaciones de Popurrí Estudio (diseño, producción y montaje). Es una sola página: `index.html`.

## Publicar con GitHub Pages
1. Settings → Pages → Source: *Deploy from a branch* → rama `main`, carpeta `/ (root)`.
2. Cuando el DNS de popurriestudio.cl apunte a GitHub, escribir `popurriestudio.cl` en *Custom domain* y activar *Enforce HTTPS*.

## Apuntar el dominio popurriestudio.cl (en NIC Chile o donde esté el DNS)
- Registros `A` para `popurriestudio.cl`: 185.199.108.153 · 185.199.109.153 · 185.199.110.153 · 185.199.111.153
- Registro `CNAME` para `www`: `<usuario>.github.io`

El cambio de DNS puede tardar algunas horas.

## Importante
Fuera de Claude, las cotizaciones y los valores base se guardan en el navegador de cada persona (localStorage): no se comparten entre computadores.
