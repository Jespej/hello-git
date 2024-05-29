# Resumen de Git

## Conceptos Básicos

- **Repositorio**: Almacén de archivos y su historial de cambios. Puede ser local (en tu máquina) o remoto (en un servidor).

- **Commit**: Instantánea de los cambios en un repositorio. Cada commit tiene un mensaje descriptivo y un identificador único (hash).

- **Rama (Branch)**: Línea de desarrollo independiente en un repositorio. Permite trabajar en características o arreglos de errores sin afectar la rama principal.

- **HEAD**: Puntero especial que indica el último commit realizado en la rama actual.

## Comandos Básicos

- `git init`: Inicializa un nuevo repositorio Git en un directorio.

- `git clone URL`: Clona un repositorio remoto en tu máquina.

- `git add archivo`: Agrega cambios de un archivo al área de preparación (staging).

- `git commit -m "mensaje"`: Confirma los cambios en el área de preparación, creando un nuevo commit con un mensaje descriptivo.

- `git status`: Muestra el estado actual del repositorio y los archivos modificados.

- `git log`: Muestra el historial de commits del repositorio.

- `git push`: Envía los commits locales a un repositorio remoto.

- `git pull`: Obtiene los cambios desde un repositorio remoto y los fusiona con el repositorio local.

- `git checkout`: Cambia entre ramas o restaura archivos a estados anteriores.

- `git branch`: Lista, crea o borra ramas en el repositorio.

- `git merge`: Fusiona cambios de una rama a otra.

- `git diff`: Muestra las diferencias entre archivos o commits.

- `git config --global`: Configura opciones de Git a nivel global en tu sistema.

## Flujos de Trabajo

1. **Crear y Confirmar Cambios**:
   - `git init`
   - `git add archivo`
   - `git commit -m "mensaje"`

2. **Sincronizar con un Repositorio Remoto**:
   - `git remote add origin URL`
   - `git push -u origin rama`

3. **Colaborar en Proyectos**:
   - `git clone URL`
   - `git branch nombre_rama`
   - `git checkout nombre_rama`
   - `git add archivo`
   - `git commit -m "mensaje"`
   - `git push origin nombre_rama`

## Notas Adicionales

- Usa `.gitignore` para especificar archivos que Git debe ignorar.
- Aprende y practica comandos Git regularmente para mejorar tu fluidez y eficiencia.

