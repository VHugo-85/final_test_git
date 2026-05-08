# Pipeline de Análisis — Heart Disease Dataset
Análisis exploratorio del dataset cardiovascular de la UCI.
El pipeline carga, limpia y analiza 303 registros clínicos
para explorar patrones asociados a enfermedades cardíacas.
## Autor
[Tu nombre completo]
Instituto de Analítica y Negocios — Lima, Perú
Curso 1: Git & GitHub para Data Science
## Instalación
pip install ucimlrepo pandas matplotlib seaborn
## Ejecución
Abrir y ejecutar el notebook main.ipynb en orden.
## Estructura del proyecto
data/ Datos generados por el notebook (ignorados por Git)
outputs/ Figuras y resúmenes generados (ignorados por Git)
main.ipynb Notebook principal del pipeline
README.md Descripción del proyecto
.gitignore Archivos excluidos del control de versiones
<<<<<<< HEAD

## Resultado clave
El 45.9% de los pacientes del dataset presenta enfermedad cardíaca.
ESTO ES UN CAMBIO DESDE MAIN.
=======
## Historial de la Fase 1
PS C:\Users\LAB. ENTOMOLOGICO\final_test_git> git log --oneline
4d5e4e1 (HEAD -> main) feat: cargar dataset cardiovascular desde UCI
a487e36 (origin/main, origin/HEAD) chore: agregar notebook principal del pipeline
767b575 chore: inicializar estructura del proyecto
435ca73 Create git_final_test.ipynb
5dbb7f9 Add files via upload
e95a4c9 Initialize README with project title
## Decisiones del historial
En la Fase 2 se usó ‘git reset HEAD~1‘ para deshacer un commit
cuyo mensaje no era descriptivo ("cambios"). Los archivos
modificados se conservaron y se volvieron a commitear con
un mensaje que explica claramente qué cambió y por qué.
Esta práctica es útil antes de hacer push al remoto, cuando
aún es posible reescribir el historial local sin afectar
a otros colaboradores.
- Rama visualizaciones: boxplot de colesterol agregado.
- Rama estadisticas: resumen por grupo de edad agregado.
