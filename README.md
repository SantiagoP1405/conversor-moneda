# conversor-moneda
Desafío del conversor de moneda del programa ONE de Alura Latam y Oracle. Formación "Java Orientado a Objetos". 

**EJEMPLO DE USO**


Este es un proyecto de conversor de moneda implementado en Java, que permite convertir entre varias monedas utilizando la API de ExchangeRate-API (https://www.exchangerate-api.com/). El programa ofrece una interfaz de consola donde el usuario puede elegir entre varias opciones de conversión, como convertir de Peso Mexicano a Dólar, Dólar a Euro, entre otros. Esta API contiene diversas tasas de intercambio de diversas monedas, por simplicidad, únicamente se implementaron las siguientes opciones: 

- Peso mexicano → Dólar
- Dólar → Peso Mexicano
- Peso mexicano → Euro
- Euro → Peso Mexicano
- Peso mexicano → Peso Argentino
- Peso argentino → Peso Mexicano
- Dólar → Euro
- Euro → Dólar

Sin embargo, este proyecto se presta para una posible ampliación del menú de opciones de monedas de intercambio. 

## Requisitos

- Java 8 o superior
- Conexión a Internet para acceder a la API de conversiones
- [API Key de ExchangeRate-API](https://www.exchangerate-api.com/) (ya incluida en el código, pero puedes generar una nueva clave si prefieres usar la tuya).
- Tener importada la biblioteca GSON en las dependencias del proyecto (En este caso se utilizó gson-2.10.1). 

## Instalación

1. Clona este repositorio:

    ```bash
    git clone https://github.com/SantiagoP1405/conversor-moneda.git
    ```

2. Entra en el directorio del proyecto:

    ```bash
    cd conversor-moneda
    ```

3. Abre el proyecto en un IDE o editor de código.

4. Ejecuta el archivo `Main.java` para comenzar a usar el conversor de moneda.

## Uso

1. Ejecuta el programa desde tu IDE o desde la terminal:

    ```bash
    javac com/santiagogomez/aluracursos/challenge_javapoo/Main.java
    java com.santiagogomez.aluracursos.challenge_javapoo.Main
    ```

2. El programa te presentará un menú con las opciones de conversión disponibles. Ingresa el número correspondiente a la conversión que deseas realizar.

3. Ingresa la cantidad que deseas convertir, y el programa te mostrará el resultado.

4. Puedes elegir la opción `0` para salir del programa.

## Estructura del Proyecto

El proyecto está compuesto por tres clases principales:

- **Main.java**: Contiene la lógica principal para ejecutar el conversor de moneda y mostrar el menú de opciones.
- **Converter.java**: Contiene la lógica para hacer las solicitudes a la API de conversiones y calcular el resultado.
- **Currency.java**: Contiene la representación de la respuesta de la API, que incluye las tasas de conversión.

**Desarrollado por**: Santiago Patricio Gómez Ochoa

Proyecto creado como parte de los cursos de Alura Latam y Oracle para el Programa ONE.



