# DataLogger Visual Studio C# 📊🔌

Este proyecto consiste en desarrollar un programa en Visual StudioC# que establece una conexión con un puerto COM de Arduino para recibir datos y generar gráficas en tiempo real. Además, proporciona la funcionalidad de exportar los datos a un archivo CVS para su análisis posterior.

## Características 🛠️

- **Conexión con Puerto COM:** Utiliza la clase `SerialPort` de .NET para establecer una conexión bidireccional con un puerto COM de Arduino y recibir datos en tiempo real.

- **Generación de Gráficas:** Utiliza bibliotecas como `System.Windows.Forms.DataVisualization` para generar gráficas en tiempo real basadas en los datos recibidos del puerto COM.

- **Exportación de Datos:** Proporciona la capacidad de exportar los datos recibidos a un archivo CSV para su análisis posterior en herramientas externas.

## Requisitos Previos 📦

- Visual Studio 2019 (o versión superior) instalado en tu sistema.
- Conocimiento básico de programación en C#.
- Un Arduino con un programa que envíe datos a través de un puerto COM.

## Uso 📝

1. **Clonar el Repositorio:** Clona este repositorio en tu sistema local utilizando Git.

2. **Abrir en Visual Studio:** Abre el proyecto en Visual Studio 2019.

3. **Compilar y Ejecutar:** Compila y ejecuta el programa en Visual Studio. Asegúrate de seleccionar el puerto COM correcto al ejecutar el programa.

4. **Visualizar Gráficas:** Una vez que el programa esté en ejecución, podrás visualizar las gráficas generadas en tiempo real basadas en los datos recibidos del puerto COM de Arduino.

5. **Exportar Datos:** Utiliza la funcionalidad de exportación para guardar los datos en un archivo CVS para su análisis posterior.


## Contribuciones 🚀

¡Contribuciones son bienvenidas! Si tienes ideas para mejorar el programa, corregir errores o agregar nuevas características, no dudes en abrir un "issue" o enviar un "pull request".

## Créditos 🙌

Este proyecto fue creado por PICAIO SAS y está inspirado en proyectos similares de la comunidad de programadores y entusiastas de Arduino.

## Licencia 📝

Este proyecto está bajo la licencia [MIT](LICENSE).
