# Trabajo Práctico N°1: Rendimiento
## Cátedra de Sistemas de Computación, FCEFyN, UNC. 2025.
### Alumnos: Bernaus, Julieta; Di Pasquo, Franco; Viccini, Carlos Patricio.
### Profesor: Jorge, Javier.

## Tareas
- Ofimática
- Streaming
- Programación
- Compilación
- Videojuegos
- Edición de imágenes


1. Ofimática (Office Tasks)
<<<<<<< HEAD
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

3. Programación (Programming)
Geekbench: Evaluate performance with benchmarks for compiling code.
Cinebench: Although focused on 3D rendering, it offers insights into CPU performance under multi-threaded workloads that can be reflective of programming tasks.
VisBench: Specialized benchmarks for measuring performance in various IDE activities.
4. Compilación (Compilation)
OpenSSL (Compilation Test): Compile OpenSSL with various configurations and measure time.
Linux Kernel Compilation: Benchmarks that measure the time taken to compile the Linux kernel, an extensive and complex task.
GCC Compilation Benchmark: Assess the speed of compiling various codebases written in different languages.
=======
PCMark 10: This benchmark measures overall office productivity including document editing and presentation tasks.
3DMark (Time Spy): While primarily a gaming benchmark, it provides insights into performance with DirectX applications which can be relevant for graphics-heavy office applications.
Microsoft Office Performance (Excel, Word, PowerPoint): Measure tasks like opening documents, data calculations (Excel), rendering presentations (PowerPoint).
2. Streaming
OBS Studio Performance Tests: Measure CPU and GPU utilization while streaming at various resolutions and bitrates.
Handbrake Encoding Benchmark: Test encoding speeds for video files at various resolutions and formats.
Blender (Open Data Benchmarks): Use the rendering section for real-time performance benchmarks in streaming graphics.
3. Programación
Cinebench: evalúa el rendimiento del CPU y sus cores.
4. Compilación
Timed GCC Compilation Benchmark (Open Benchmarking): mide el tiempo de compilación de GCC, dependiendo del CPU y la memoria.
>>>>>>> feature/benchmarks-prog-comp
5. Videojuegos (Gaming)
3DMark: Offers different tests (like Fire Strike and Time Spy) to benchmark gaming performance.
Frame Rate Benchmarks: Measure frame rates across different titles using software like FRAPS or built-in game performance metrics.
Unity Benchmark: Use Unity's benchmark tool to assess graphics performance in a game development context.
6. Edición de imágenes (Image Editing)
Adobe Photoshop Benchmark: Use scripts to automate tasks in Photoshop, measuring performance for specific tasks like applying filters, rendering, or exporting images.
GIMP Performance Test: Benchmark specific image editing tasks like filtering, resizing, and batch processing.
CorelDRAW Performance: Run a benchmark on vector graphic rendering and manipulation.
General Considerations
Cinebench (CPU based): For rendering tasks relevant for all categories.
Storage Performance Tests: Use tools like CrystalDiskMark or ATTO Disk Benchmark to evaluate how storage speed affects all tasks, especially in I/O-heavy applications.
Cross-application Workflow Tests: Combine tasks from different categories to measure overall system performance in multitasking scenarios.
