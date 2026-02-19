# GitHub Actions Demo

Este proyecto demuestra el uso básico de GitHub Actions para automatizar flujos de trabajo de CI/CD.

## Descripción

Este repositorio contiene un ejemplo simple de un workflow de GitHub Actions que se activa cada vez que se realiza un push a cualquier rama. El workflow:

- Muestra información sobre el evento que lo activó
- Muestra detalles sobre el entorno de ejecución
- Lista los archivos del repositorio
- Verifica el estado del trabajo

## Workflow

El workflow está definido en `.github/workflows/github-actions-demo.yml` y se activa en eventos de push.

### Pasos del workflow:

1. Muestra el evento que activó el workflow
2. Muestra información sobre el sistema operativo del runner
3. Muestra el nombre de la rama y el repositorio
4. Clona el código del repositorio
5. Lista los archivos en el directorio de trabajo
6. Muestra el estado final del trabajo

## Cómo usar

1. Realiza un push a cualquier rama del repositorio
2. Ve a la pestaña "Actions" en tu repositorio de GitHub
3. Observa cómo se ejecuta el workflow automáticamente

## Próximos pasos

- Personalizar el workflow para proyectos específicos
- Añadir pruebas automatizadas
- Configurar despliegues automáticos
- Implementar análisis de código

Para más información sobre GitHub Actions, consulta la [documentación oficial](https://docs.github.com/en/actions).