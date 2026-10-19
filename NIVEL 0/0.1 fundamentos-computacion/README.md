# Fundamentos de Computación e Internet

## 📚 Descripción

Con este proyecto se busca comprender mejor, el funcionamiento de una computadora y del internet en el uso cotidiano del día.

## 🎯 Objetivos

* Aprender el lenguaje de la computadora (bits, binarios).
* Comprender el funcionamiento de las IP.
* Analizar la función del DNS.
* Determinar el renderizado de una página Web.
* Conocer herramientas cómo:
  * Devtools.
  * CMD/Powershell (ping, nslookup).
* Descubrir los distintos códigos HTTP.
* Determinar la diferencia entre HTTP y HTTPS.
* Investigar sobre el recorrido de una URL.

## 🧠 Conceptos aprendidos

### Hardware

1. CPU
2. RAM
3. Memoria de almacenamiento (SSD)

### Sistema operativo y procesos

1. Windows OS
2. Administrador de tareas de Windows.

### Sistema binario y hexadecimal

1. Binario:
    * Los sistemas digitales representan y procesan información internamente mediante estados que podemos representar con bits (**0** y **1**).
2. Hexadecimal:
    * Utilización de 16 símbolos (**0 - 9** y **A - F**) empezando del 0 y terminando en el 15.

### Redes

1. Uso de herramientas cómo:
    * CMD o Powershell
2. Uso de comandos cómo:
    * ping
    * nslookup

### DNS

1. Sistema encargado de tomar el dominio, determinar una o más direcciones IP asociadas al dominio y devolverlas al cliente/resolvedor DNS.

### HTTP y HTTPS

1. Protocolo de comunicación utilizado para intercambiar recursos e información entre clientes y servidores. Mayormente usado en navegadores Web.
2. HTTP/1.1 y HTTP/2 utilizan TCP, mientras que HTTP/3 utiliza QUIC sobre UDP para comunicarse, y obtiene códigos cómo 2xx, 3xx, 4xx o 5xx que determina el resultado de la solicitud que se haya realizado.
3. HTTPS es la conexión protegida de HTTP que utiliza TLS cómo protocolo de protección.

### Modelo cliente-servidor

1. Cliente es el componente que realiza solicitudes a un servidor para obtener recursos o ejecutar operaciones en su nombre.
2. Servidor recibe y procesa las solicitudes de los clientes y proporciona las respuestas correspondientes.

### Recorrido de una URL

1. Usuario escribe una URL
        ↓
2. Navegador (cliente) interpreta la URL
        ↓
3. DNS resuelve dominio y entrega la IP
        ↓
4. Cliente se comunica con el servidor mediante HTTP/HTTPS
        ↓
5. Servidor procesa la solicitud
        ↓
6. Servidor devuelve una respuesta HTTP
   (código + contenido/recursos cuando corresponda)
        ↓
7. Cliente recibe y procesa la respuesta
        ↓
8. Navegador renderiza la página
        ↓
9. ¿Necesita otros recursos?
       / \
     Sí   No
     ↓     ↓
Nuevas   Página
peticiones finalizada

## 🧪 Ejercicios realizados

* Conversión decimal a binario.
* Identificar procesos y su consumo de recursos de windows.
* Diagnóstico de red con *ping* y *nslookup*.
* DevTools -> Network(Red) en *Google Chrome*.
* Recorrido de una petición Web.

## 🔎 Observaciones y aprendizajes

* Por medio de los diferentes ejercicios y la teoría se entiende que:
  1. Los computadores o máquinas usan únicamente el binario para leer, entender, procesar, renderizar y realizar un sin fin de tareas mientras que los humanos usamos alfabetos y números decimales para lo mismo.
  2. Se puede hacer un diagnóstico parcial de la calidad de red y la conexión de un servidor, por medio de comandos a través de la terminal.
  3. Se evidencia los diferentes aplicativos que un equipo puede correr en primer o segundo plano y su consumo, a través de herramientas cómo *Administrador de tareas* de Windows.
  4. Se ubica y conoce todo lo que un navegador puede procesar a través de la cabecera de HTTP para la obtención y posterior renderización de una URL, gracias a herramientas cómo *DevTools -> Network (Red)*. Entre estas:
        * Request URL: <https://example.com/>
        * Method: GET
        * Status Code: 304
        * Type: document
        * Observaciones: Age 474, server cloudflare, last-modified tue 13 oct 2026 22:05:48 GMT, scheme https, entre otras.
  5. Se profundiza en cómo por debajo de lo que el usuario final, un cliente (navegador) realiza todo el proceso para llevar de una URL escrita hasta la renderización de esta misma.

## 🛠️ Herramientas utilizadas

* CMD/Powershell.
* DevTools de Chrome.
* Administrador de tareas de Windows.

## 📈 Estado del proyecto

* Versión: **2.0**
* Estado: **Finalizado**.
