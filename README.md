# Okonomi

økonomi es una aplicación diseñada para recopilar y analizar tickets y compras, con el objetivo de ofrecer un análisis financiero doméstico a los usuarios. Este proyecto está construido con tecnologías modernas como Nest.js para el backend y React.js para el frontend.

## Características

- Conexión con Gmail para extraer tickets de Mercadona y correos de PayPal.
- Almacenamiento de información relevante en una base de datos MySQL.
- Interfaz de usuario para visualizar y analizar las compras almacenadas.
- Funcionalidades de análisis para identificar tendencias financieras.






## Start the application

Run `npx nx serve Okonomi` to start the development server. Happy coding!


## Build for production

Run `npx nx build Okonomi` to build the application. The build artifacts are stored in the output directory (e.g. `dist/` or `build/`), ready to be deployed.

## Running tasks

To execute tasks with Nx use the following syntax:

```
npx nx <target> <project> <...options>
```

You can also run multiple targets:

```
npx nx run-many -t <target1> <target2>
```

..or add `-p` to filter specific projects

```
npx nx run-many -t <target1> <target2> -p <proj1> <proj2>
```

Targets can be defined in the `package.json` or `projects.json`. Learn more [in the docs](https://nx.dev/features/run-tasks).

## Licencia

Este proyecto está bajo la licencia [MIT](LICENSE).
```
