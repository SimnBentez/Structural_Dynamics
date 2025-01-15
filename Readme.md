# STRUCTURAL DYNAMICS

## [ES] ESPAÑOL

Este repositorio se ha desarrollado para obtener la respuesta dinámica de un edificio completamente simétrico con el número de pisos que el usuario desee. La respuesta se puede calcular considerando la interacción del suelo ante un sismo armónico idealizado o utilizando el espectro de respuesta proporcionado por el usuario. Es importante que el usuario lea los comentarios en el código, los cuales explican de manera detallada la funcionalidad de cada función y el proceso de ejecución del programa.

Además, se incluyen gráficos y cálculos relacionados con las derivas (diferencia de desplazamientos con respecto a la altura), los cortantes, los momentos flectores, el cortante basal, el momento basal, así como los valores máximos de todos estos parámetros. En caso de simular un sismo, se genera una animación en formato GIF de la respuesta estructural, que se guarda automáticamente en el mismo directorio donde se encuentra el notebook de Jupyter.

### Consideraciones

El programa se basa en ciertas aproximaciones, tales como:

* Se asume que todos los pisos tienen la misma masa.
* La matriz de rigidez se calcula utilizando el modelo de Euler-Bernoulli.
* Se considera que todos los pisos tienen la misma configuración de columnas, y se asume que las vigas no tienen deformación axial, es decir, que son infinitamente rígidas en esa dirección.

## [EN] ENGLISH

This repository is designed to obtain the dynamic response of a fully symmetric building with any number of floors specified by the user. The response can be calculated by considering the soil’s interaction under a perfectly harmonic earthquake or using the response spectrum provided by the user. It is essential for the user to read the comments in the code, as they explain in detail the purpose of each function and the execution process.

Additionally, the repository includes graphs and calculations related to drifts (displacement differences with respect to height), shear forces, bending moments, base shear, base moment, and the maximum values for all of these parameters. In the event of simulating an earthquake, a GIF animation of the structural response is generated and saved in the same directory as the Jupyter notebook.

### Considerations

The program is based on certain assumptions, such as:

* All floors are assumed to have the same mass.
* The stiffness matrix is calculated using the Euler-Bernoulli beam theory.
* All floors have the same column configuration, and it is assumed that the beams do not experience axial deformation, meaning they are infinitely rigid in that direction.