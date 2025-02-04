Instrucciones para ejecutar el código - COMPARACIÓN VISUAL ENTRE ALGORITMOS:

1. Abrir la carpeta del proyecto:
   - Navega a la siguiente dirección en el CD:
     ANÁLISIS COMPARATIVO DE ALGORITMOS DE MACHINE LEARNING SUPERVISADO PARA LA CLASIFICACIÓN DE FALLAS DE MAQUINARIA INDUSTRIAL\[Nombre de la carpeta del código]

2. Abrir Visual Studio Code:
   - Lanza Visual Studio Code.

3. Abrir la carpeta en VS Code:
   - Haz clic en Archivo > Abrir Carpeta...
   - Selecciona la carpeta que contiene el código para la "COMPARACIÓN VISUAL ENTRE ALGORITMOS".

4. Verificar los archivos de entrada:
   - Asegúrate de que los archivos "X_test.pkl" y "y_test.pkl" estén ubicados en la carpeta del proyecto.
   - También verifica que los archivos de los algoritmos estén presentes:
     - Algoritmo_regresion_logistica1.pkl
     - Algoritmo_arboles1.pkl
     - Algoritmo_bosques1.pkl
     - Algoritmo_gbm1.pkl
     - Repite estos archivos cambiando el número "1" por "2" y luego por "3", para obtener las versiones correspondientes a los diferentes conjuntos de datos (completo, oversampling, undersampling).

5. Ejecutar el código:
   - Abre el archivo de código (ya sea un archivo .py o un Jupyter Notebook).
   - Ejecuta el código, el cual cargará primero los archivos "X_test.pkl" y "y_test.pkl".
   - A continuación, el código leerá los 12 archivos correspondientes a cada algoritmo y conjunto de datos, realizando la comparación visual entre ellos.