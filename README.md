# Proyecto_Final_Inteligencia_Artificial
Este proyecto consta de una página web creada con Flask. La página le permite a los usuarios utilizar diversos algoritmos de Machine Learning sobre ciertos datos.

CONSIDERACIONES:
- Dentro de la carpeta "Datos" se encuentran algunos archivos .csv que se pueden utilizar en los algoritmos de ML. Cada algoritmo soporta diferentes archivos específicos, si se tiene algún error con X algoritmo al utilizar X archivo para correrlo, es porque ese archivo no está soportado dentro del algoritmo, intentar con otro archivo hasta que se logre laa ejecución correcta del algoritmo.
- Sobre el anterior punto, eso se puede arreglar al incluir dentro de cada algorimo opciones para preparar los datos. Como son algoritmos de ML, es bien sabido que cada archivo CSV de entrada puede contener diferentes dimensiones de columnas, así como cada columna puede contener diferentes tipos de datos. No pudimos implementar la modificación en tiempo real a los datos en la página web debido a que no teníamos el conocimiento necesario. Este punto sería un TO-DO.
- Para correr el código basta con abrir el folder el Visual Studio Code y correr el archivo 'fusion_app.py' con el comando 'python fusion_app.py'. Se generará un link como el siguiente: http://127.0.0.1:5100
- Abrir ese link en el navegador que se prefiera para ver la página web.
- Si no se compila el código será porque no se tienen instaladas todas las bibliotecas necesarias, descargarlas (son varias, así que tómese su tiempo). Para instalar cada biblioteca basta con utilizar el comando "pip install <biblioteca>" y ya.
