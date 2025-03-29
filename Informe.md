# Trabajo Práctico N°1: Rendimiento
## Cátedra de Sistemas de Computación, FCEFyN, UNC. 2025.
### Alumnos: Bernaus, Julieta; Di Pasquo, Franco; Viccini, Carlos Patricio.
### Profesor: Jorge, Javier.

## Introducción
En este informe, se utilizará el concepto de benchmarking para evaluar el rendimiento de diferentes CPU. En primer lugar, utilizaremos algunas de las herramientas de terceros disponibles en el mercado para evaluar el rendimiento de algunos procesadores. En segundo lugar, utilizaremos herramientas para obtener nuestros propios resultados.

## Desarrollo
### Tareas
- Ofimática
- Streaming
- Programación
- Compilación
- Videojuegos
- Edición de imágenes


1. Ofimática (Office Tasks)
PCMark 10: es un sistema de evaluación comparativa para PC con Windows centrado en tareas ofimáticas modernas. Ofrece diversas cargas de trabajo clasificadas en cuatro grupos. El grupo Essentials incluye navegación web, videoconferencia y tiempo de arranque de aplicaciones. El grupo Productividad incluye pruebas basadas en hojas de cálculo y escritura. El grupo de Creación de Contenidos Digitales incluye edición de fotos, edición de vídeo y una prueba de renderizado y visualización. El último grupo, Juegos, incluye pruebas de gráficos en tiempo real y física.
El benchmark PCMark 10 comprueba el rendimiento utilizando los grupos Essentials, Productivity y Digital Content Creation.
La prueba PCMark 10 Express incluye los grupos Essentials y Productivity.
La prueba PCMark 10 Extended incluye los grupos Essentials, Productivity, Digital Content Creation y Gaming.
Elegimos éste porque realizamos principalmente tareas ofimáticas en Windows.

2. Video Call Streaming
Zoom NetworkConnectivity Tool (Meeting test): sirve para simular una video llamada. La herramienta probará e informará sobre cada uno de los siguientes elementos cuando la prueba esté completa
- Latencia (RTT): Prueba el retraso en las comunicaciones entre el dispositivo y los servidores de Zoom.
- Pérdida de Paquetes: Prueba el porcentaje de pérdida de paquetes de datos entre el dispositivo y los servidores de Zoom.
- Jitter: Prueba la variación de latencia entre el dispositivo y los servidores de Zoom.
- Códec: Enumera el códec de audio utilizado para enviar y recibir durante la prueba.
- Frecuencia de Reloj (KHz)

3. Programación
Cinebench: evalúa el rendimiento del CPU y sus cores.

4. Compilación
Timed GCC Compilation Benchmark (Open Benchmarking): mide el tiempo de compilación de GCC, dependiendo del CPU y la memoria.

5. Videojuegos (Gaming)
- 3DMark: Es una herramienta creada por UL Benchmarks para determinar el rendimiento de la renderizacion de graficos 3D y la capacidad de procesamiento de la carga de trabajo de la CPU. Al ejecutar 3D Mark se obtiene una puntuacion 3DMark normalizada, basada en los valores obtenidos del "GPU Score" y la "CPU Score", generando un "Overall Score". 

6. Edición de imágenes (Image Editing)
- Adobe Photoshop Benchmark: Prueba de rendimiento utilizada para evaluar el desempeño de una computadora al ejecutar tareas en Adobe Photoshop. Utiliza diversas herramientas y recursos del sistema, incluyendo:
    - CPU → Procesamiento de imágenes, filtros y efectos.
    - GPU → Aceleración gráfica en ciertas tareas.
    - RAM → Carga y manipulación de imágenes de gran tamaño.
    - Almacenamiento (SSD/HDD) → Velocidad de lectura/escritura de archivos grandes.
    - Sistema Operativo → Puede afectar el rendimiento según la optimización de controladores y administración de recursos. 


### Fórmulas
#### Rendimiento

$$T_{instruccion} = CPI * T_{CPU}$$
$$T_{prog} = N°instrucciones * CPI * T_{CPU}$$
$$\eta_{prog} = \frac{1}{T_{prog}}  = \frac{1}{N°instruc * CPI * T_{CPU}} = \frac{f_{CPU}}{N°instruc * CPI} s^{-1}$$

#### Desempeño
$$Speedup = \frac{Rendimiento mejorado}{Rendimiento original} = \frac{EX_{CPU original}}{EX_{CPU mejorado}}$$

#### Eficiencia
$$Eficiencia = \frac{Speedup_n}{n}$$
