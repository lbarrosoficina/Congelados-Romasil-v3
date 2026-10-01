# Congelados Romasil — Versión 3

Propuesta visual independiente del sitio estático de Congelados Romasil. El contenido está en `dist/`.

- Repositorio de esta versión: `Congelados-Romasil-v3`
- Rama principal: `main`
- Estado: prototipo visual, sin despliegue conectado
- Producción actual: <https://congeladosromasil.cl/>

## Aislamiento de producción

Este repositorio es independiente de `lbarrosoficina/Congelados-Romasil`. No está conectado a los proyectos de Vercel o Netlify que sirven la web de producción. Subir cambios aquí no debe iniciar ni modificar los despliegues del sitio actual.

## Documentación por área

- [Operación de la web](docs/WEB.md): NIC Chile, Cloudflare DNS, GitHub, Netlify y Vercel.
- [Operación del correo](docs/CORREO.md): Gmail, Cloudflare Email Routing, Resend y FormSubmit.
- [Cómo iniciar otra conversación](docs/INICIAR-CONVERSACION.md): textos listos para separar el trabajo de web y correo.
- [Instrucciones para agentes](AGENTS.md): reglas obligatorias de trabajo y publicación por lotes.

## Regla principal de publicación

Los cambios se acumulan y prueban localmente. No se crea un commit ni se sube nada a GitHub hasta que el usuario diga expresamente “publica los cambios”, “sube a GitHub” o “cierra el lote”.

Los cambios de esta versión se publican únicamente en su repositorio independiente. No conectar este repositorio a los proyectos de producción existentes en Vercel o Netlify.

## Seguridad

No guardar en GitHub contraseñas, códigos de verificación, claves API, tokens ni credenciales. Las claves necesarias para servicios externos deben almacenarse como variables de entorno en la plataforma correspondiente.
