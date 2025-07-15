# Proyecto de Generación de Números Aleatorios

Este repositorio contiene varios proyectos relacionados con la generación de números aleatorios utilizando diferentes métodos y fuentes de datos. Los proyectos están organizados en carpetas según su propósito y funcionalidad.

>[!WARNING]
>para saber exactamente la funcionalidad de los códigos y saber que pretendía cada uno han sido pasados por IA.


## Carpetas

1. **CSPRNG_1: Datos Climáticos**
   - Genera números aleatorios basados en datos climáticos obtenidos de la API de OpenWeatherMap.
   - Incluye dos programas:
     - Programa 1: Genera números aleatorios combinando datos climáticos y ruido simulado.
     - Programa 2: Obtiene y muestra la temperatura actual de una ciudad seleccionada al azar.
```
Datos Climáticos

Esta carpeta contiene dos programas que utilizan la API de OpenWeatherMap
para obtener datos climáticos y generar números aleatorios.

## Programa 1: Generación de Números Aleatorios con Ruido Simulado

Este programa obtiene datos climáticos de una ciudad seleccionada al azar y utiliza
un modelo de ruido simulado del ventilador de la CPU para generar números aleatorios.

Requisitos

- Python 3.x
- Bibliotecas: `requests`, `random`, `time`

## Programa 2: Obtención de Temperatura Actual
Este programa obtiene y muestra la temperatura actual de una ciudad seleccionada al azar.

Requisitos
Python 3.x
Bibliotecas: requests, random

```


2. **CSPRNG_2: Audio**
   - Utiliza la biblioteca `pyaudio` para grabar audio y generar números aleatorios.
   - Incluye dos programas:
     - Programa 1: Genera números aleatorios combinando datos de audio y datos climáticos.
     - Programa 2: Graba audio y lo guarda como un archivo WAV.
    
```

Esta carpeta contiene dos programas que utilizan la biblioteca `pyaudio` para
trabajar con audio.

- Programa 1: Generación de Números Aleatorios con Audio

Este programa graba audio, procesa los datos de amplitud y genera números
aleatorios combinados con datos climáticos obtenidos de la API de OpenWeatherMap.

* Requisitos

- Python 3.x
- Bibliotecas: `pyaudio`, `struct`, `random`, `requests`

- Programa 2: Grabación de Audio
Este programa graba audio durante 5 segundos y lo guarda como un archivo WAV.

Requisitos
Python 3.x
Bibliotecas: pyaudio, wave

```

3. **CSPRNG_3: Cadenas Aleatorias**
   - Genera cadenas aleatorias utilizando las bibliotecas `os` y `random`.
  
```
## Funcionalidad

El programa genera una lista de 10 cadenas aleatorias de longitud 10,
compuestas por letras y dígitos.

### Requisitos

- Python 3.x
- Bibliotecas: `os`, `random`, `string`

```

4. **CSPRNG_4: Números Aleatorios Seguros**
   - Genera números aleatorios utilizando la biblioteca `secrets`, diseñada para aplicaciones criptográficamente seguras.
  
```
Funcionalidad

El programa genera una lista de 10 números aleatorios en el rango de 1 a 10000.

### Requisitos

- Python 3.x
- Bibliotecas: `secrets`
```
  
### README creado por TecXion

<h3 align="center"><img src="https://github.com/tecxion/TecXion/blob/main/Media/TECXARTgif2.gif"></h3>

