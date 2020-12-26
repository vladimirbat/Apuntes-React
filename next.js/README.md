# NEXT.js
Next.js es un Framework de React (recuerdese que React es una biblioteca, no un framework) que proporciona un conjunto de herramientas que facilitan el desarrollo en React.
## Características

1. **Renderizado en el lado del servidor (SSR)**: permite realizar aplicaciones isomorficas o universales, que se renderizane
2. **Prerenderizado**: en el build se analizan las páginas cuyo renderizado inicial va a ser predecible y durante el build realiza ese renderizado inicial para emplearlo en la primera carga de esa página, lo que proporciona una rendimiento excepcional.
3. **Exportación de estáticos**: adicionalmente permite generar sitios estáticos.
4. **Configuración Cero**: por defecto viene con las herramientas necesarias preconfiguradas.
5. **Extensible**: no necesita ejección para poder extenderse y ampliar sus fucionalidades.
6. **Styled JSX**: biblioteca que permite agregar estilos encapsulados en el componente (internamente agrega una clase de defensa para el componente).
7. **Rutas API**: creación de API del lado del servidor para conexión hacia otras fuentes de datos, CMS, microservicios y permite el uso de GraphQL.
8. **AMP**: permite crear aplicaciones APM.
9. **TypeScript**: permite realizar el desarrollo con TypeScript.
10. **Variables de entorno**: parametrizable mediante variables de entorno.
11. **Fast Refresh**: en el servidor de desarrollo, realiza una actualización casi instantánea de los cambios realizados en el código. Esto se consigue mediante un cache guardado en la carpeta '.next'. 
12. **next/head**: permite mejorar la información ofrecida por la página y por lo tanto su seo, para ello proprciona una etiqueta <Head>, dentro de la cual se puede indicar los datos de identificación de la página.

## Instalación

```javascript
    npx create-next-app
    npm install --save-dev typescript @types/react @types/node
```


