# Ejercicio 1: React Issues

En el repositorio de github de React, existe una sección donde se muestran los issues del proyecto: [React Issues](https://github.com/facebook/react/issues).

Desarrolla un programa en React con componentes que consulte la API de los issues del proyecto de React y muestre un listado de los issues en la pantalla, con las siguientes características:

## Características:

1. **Cargar la página:** Al cargar la página, se mostrará el listado de issues.
2. **Listado de issues:** Cada ítem del listado deberá:
   - Mostrar el id del issue.
   - Mostrar el título del issue.
   - Mostrar el nombre del usuario que abrió el issue.
3. **Enlace al detalle:** Cuando haga clic en un título, deberá mandar al enlace que tiene el detalle del issue en GitHub (ejemplo: [Issue Detalle](https://github.com/facebook/react/pull/24117)) - (html_url).

## Plus:

- Mostrar los labels a los que pertenece cada issue (ejemplo: Status: Unconfirmed, React 18, etc.).
- Elaborar una barra de búsqueda, que permita filtrar los resultados traídos por la API.

## Consideraciones:

- Recuerda que las llamadas a la API deberán estar dentro del hook de React de `useEffect()`.
- El endpoint a utilizar con la información de los issues es: [GitHub Issues API](https://api.github.com/repos/facebook/react/issues).

Un ejemplo podría ser el siguiente: [React Issues App](https://josemiguelvazquez.github.io/react-issues-app/)
