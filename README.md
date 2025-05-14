# Algoritmo de Shor para la Factorización de Números

Este proyecto implementa el **algoritmo de Shor** para la factorización de números utilizando enfoques clásicos y cuánticos. El algoritmo de Shor es un algoritmo cuántico que puede factorizar grandes números de forma eficiente, utilizando el poder de la computación cuántica.

## Notebooks Incluidos

1. **Shor's Algorithm Implementation**: Este notebook implementa el algoritmo de Shor para factorizar números utilizando tanto operaciones clásicas como cuánticas.
2. **Classical Factorization Methods**: Explora métodos clásicos de factorización, como el uso de **algoritmos de Euclides** para calcular el **máximo común divisor (GCD)** y la búsqueda de periodos en funciones exponenciales modulares.
3. **Quantum Circuit Simulation**: Muestra la simulación de los circuitos cuánticos que son utilizados en el algoritmo de Shor, específicamente la Transformada Cuántica de Fourier (QFT), para encontrar el periodo \( r \).
4. **Factorization with Shor's Algorithm**: En este notebook se explora cómo, basándose en el periodo \( r \) encontrado cuánticamente, se pueden calcular los factores de un número \( N \) utilizando el **GCD** y la factorización modular.

## Getting Started

Estas instrucciones te ayudarán a obtener una copia del proyecto y a ejecutarlo en tu máquina local para desarrollo y pruebas.

### Prerequisitos

Asegúrate de tener Python 3.x instalado en tu máquina local.

Instala las dependencias necesarias con pip (si es que hubiera alguna, aunque este proyecto no tiene dependencias externas):

## Running the tests

Para ejecutar las pruebas automatizadas de este sistema, utilizamos el framework `unittest` de Python. Las pruebas aseguran que todas las graficas y las matrices se evidencien en cada uno de los ejercicios.

### Break down into end to end tests

Para garantizar la precisión de la simulación, se han diseñado pruebas end-to-end que validan cada fase del proceso:

Validación de parámetros: Se verifica que los valores de entrada (distancias, longitudes de onda, etc.) sean coherentes y estén dentro de los rangos esperados.

Cálculo de interferencia: Se comparan los resultados del patrón de interferencia con valores teóricos.

Generación de gráficos: Se inspecciona la correcta visualización de los diagramas de barras

## Deployment

Para desplegar este proyecto en un sistema en vivo, simplemente configura un servidor Python y asegúrate de que el entorno de desarrollo esté correctamente instalado.

## Built With

* [Python](https://www.python.org/) - El lenguaje utilizado
* [unittest](https://docs.python.org/3/library/unittest.html) - Framework de pruebas automatizadas utilizado

## Contributing

Por favor, lee [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) para detalles sobre el código de conducta y el proceso para enviar pull requests.

## Versioning

Utilizamos [SemVer](http://semver.org/) para el versionado. Para las versiones disponibles, consulta las [etiquetas en este repositorio](https://github.com/tu_usuario/calculo_numeros_complejos/tags).

## Authors

* Oscar Santiago Merino Suarez - Tarea - [TuGithub](https://github.com/tu_usuario)

Consulta también la lista de [colaboradores](https://github.com/tu_usuario/calculo_numeros_complejos/contributors) que participaron en este proyecto.

## License

Este proyecto está bajo la Licencia MIT - consulta el archivo [LICENSE.md](LICENSE.md) para más detalles.

## Acknowledgments

* Agradecimientos a aquellos cuya código ha sido utilizado
