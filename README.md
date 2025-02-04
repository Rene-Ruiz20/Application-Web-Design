# Application-Web-Design

# Información Personal

- **Nombre:** [Rene]
- **Matrícula:** [al03045023]
- **Carrera:** [IDS]
- **Semestre:** [6to]

## Información de la Asignatura

- **Nombre de la Asignatura:** [Diseño de aplicaciones web]
- **Profesor:** [Desmond]

## ¿Qué es Markdown?

Markdown es un lenguaje de marcado ligero que se utiliza para dar formato a texto en documentos, especialmente en archivos README. Se emplea para:
- Crear títulos, listas, enlaces, tablas, entre otros.
- Documentar proyectos en repositorios como GitHub.
- Generar contenido fácil de leer tanto en texto plano como en versiones renderizadas.

## Opciones de Etiquetado en Markdown

Markdown es un lenguaje de marcado ligero que permite dar formato a documentos de texto plano. Algunas de las opciones de etiquetado que ofrece son:

### Encabezados:
```markdown
# Encabezado de nivel 1
## Encabezado de nivel 2
### Encabezado de nivel 3

### Estilos de texto:
```markdown
*Texto en cursiva* o _Texto en cursiva_
**Texto en negrita** o __Texto en negrita__
~~Texto tachado~~
```

### Listas:
```markdown
- Elemento de lista 1
- Elemento de lista 2
  - Sub-elemento 1
  - Sub-elemento 2
```

### Enlaces e imágenes:
```markdown
[Texto del enlace](https://www.ejemplo.com)
![Texto alternativo](imagen.jpg)
```

---

## Comandos de Git

Aquí están algunos comandos útiles que se usan en Git:

### 1. Verificar el estado del repositorio local
```bash
git status
```

### 2. Agregar archivos al área de preparación (staging)
```bash
git add nombre_del_archivo  # Para agregar un solo archivo
git add .                   # Para agregar todos los archivos modificados
```

### 3. Realizar un commit con un mensaje
```bash
git commit -m "Mensaje descriptivo del commit"
```

### 4. Subir los cambios al repositorio remoto
```bash
git push origin main
```

### 5. Crear, cambiar y eliminar ramas
```bash
git branch nueva_rama          # Crear una nueva rama
git checkout nueva_rama        # Cambiar a la nueva rama
git checkout -b nueva_rama     # Crear y cambiar a una nueva rama en un solo paso
git branch -d nombre_de_rama   # Eliminar una rama local
git push origin --delete nombre_de_rama  # Eliminar una rama remota
```

### 6. Retroceder a un commit anterior
```bash
git log                       # Ver el historial de commits
git checkout ID_DEL_COMMIT    # Volver a un commit específico (modo lectura)
git reset --hard ID_DEL_COMMIT  # Retroceder y eliminar cambios posteriores
