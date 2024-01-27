# pim-memorias-tesis
Temas disponibles para Proyectos de Ingeniería Mecánica, Memorias de Título y Tesis de Magíster. Otros temas a convenir. 
Contacto al correo fleaman@udec.cl

## 1. Un método para selección de wavelet madre en el análisis de emisiones acústicas mediante la transformada wavelet
#### Descripción
En el análisis de emisiones acústicas (AE) en materiales, las herramientas basadas en la transformada wavelet tienen la capacidad de generar mejores resultados que herramientas basadas en la transformada Fourier. Sin embargo, un paso importante dentro de este análisis es la selección de la wavelet madre a utilizar. Esto es clave para obtener resultados satisfactorios, ya que una incorrecta selección de la wavelet madre puede llevar a conclusiones incorrectas. En el trabajo se evaluará un método de selección de wavelet madre basado en fuentes de AE del tipo Hsu-Nielsen.
#### Objetivo principal
Evaluar una propuesta de método para selección de wavelet madre en el análisis de AE en materiales.
#### Temario
* Investigación bibliográfica sobre AE
* Investigación bibliográfica sobre la transformada wavelet
* Programación del método de selección de wavelet
* Realización de experimentos para algunos casos simples
* Evaluación del método con datos experimentales de AE


## 2. Concepto de una descomposición modal empírica rápida para el análisis de señales
#### Descripción
La descomposición modal empírica (EMD) se usa para analizar señales complejas mediante su descomposición en diferentes funciones modales intrínsecas. El algoritmo para llevar a cabo esta descomposición es intensivo computacionalmente, por lo que la aplicación de la EMD en señales adquiridas con una alta tasa de muestreo puede llegar a ser sumamente lenta. Un ejemplo de esto son las señales de emisiones acústicas (AE).
#### Objetivo principal
Proponer un concepto de software para llevar a cabo una descomposición empírica rápida y comparar sus resultados con el algoritmo clásico.
#### Temario
* Investigación  bibliográfica sobre análisis de señales
* Análisis detallado del algoritmo clásico de EMD
* Desarrollo de propuestas para un algoritmo rápido
* Evaluación comparativa con señales simuladas de AE
* Evaluación comparativa con señales experimentales de AE


## 3. Modelación de sistemas dinámicos mediante redes neuronales artificiales
#### Descripción
Las redes neuronales artificiales (ANN) son en la actualidad el método más versátil dentro del aprendizaje automático (machine learning) para generar modelos de clasificación y regresión a partir de datos. Es decir, ellas tienen la capacidad de aprender las relaciones funcionales entre datos de entrada y datos de salida sin la necesidad de definir las ecuaciones analíticas que gobiernan el fenómeno en cuestión. En los últimos años han surgido tipos de ANN que son capaces de predecir el comportamiento de sistemas dinámicos sin la necesidad de establecer las ecuaciones diferenciales del movimiento, lo cuál tiene un gran potencial dentro de la ingeniería mecánica. Existen modelos que utilizan ANN clásicas como el perceptrón multicapa, o bien modelos más avanzados que utilizan las formulaciones de la mecánica de Lagrange y de Hamilton.
#### Objetivo principal
Establecer modelos de ANN que permitan modelar el movimiento de sistemas dinámicos del tipo masa-resorte-amortiguador.
#### Temario
* Investigación bibliográfica sobre ANN
* Simulación numérica de sistemas dinámicos
* Diseño y programación de modelos ANN en Python
* Comparación de resultados de modelos ANN con resultados analíticos
* Aplicación a caso experimental en laboratorio


## 4. Diagnóstico de fallas en máquinas mediante clasificación automática de imágenes tiempo-frecuencia
#### Descripción
Una poderosa herramienta de análisis para el diagnóstico de fallas en máquinas son las transformadas tiempo-frecuencia. Algunas de ellas son la transformada corta de Fourier, las transformadas wavelet o la transformada Hilbert-Huang, entre otras. Estas transformadas se usan para generar una representación gráfica (imagen) de la distribución de energía de una señal vibratoria en los dominios tiempo y frecuencia. Debido a la compleja interpretación de sus resultados, se hace necesario contar con metodologías que permitan un análisis con mayor grado de automatización. En este sentido, las técnicas del aprendizaje automático para clasificación de imágenes tienen un gran potencial para avanzar en esta dirección.
#### Objetivo principal
Desarrollar una metodología de clasificación automática de fallas mediante imágenes tiempo-frecuencia utilizando aprendizaje automático.
#### Temario
* Investigación bibliográfica sobre transformadas tiempo-frecuencia
* Investigación bibliográfica sobre técnicas de clasificación de imágenes
* Definir casos de estudio de fallas a considerar
* Diseño y programación una metodología de análisis en Python
* Evaluación de la metodología con señales simuladas y/o medidas


## 5. Generación de datos sintéticos mediante redes generativas antagónicas para el diagnóstico de condición de máquinas
#### Descripción
En el diagnóstico de condición de máquinas mediante aprendizaje automático es común no contar con suficientes datos como uno quisiera para poder entrenar un modelo de predicción. Una forma de enfrentar esto es mediante la generación de datos sintéticos que sean diferentes a los reales, pero que a la vez sean plausibles de ocurrir. Para este efecto, las redes generativas antagónicas son algoritmos consistentes en un generador y un evaluador. El generador produce datos sintéticos en base a datos reales y el evaluador intenta descubrir si los datos que le llegan son sintéticos o reales. La idea es intentar "engañar" al evaluador hasta el punto en que no pueda distinguir entre datos reales y sintéticos.
#### Objetivo principal
Implementar red generativa antagónica para mejorar el desempeño de modelos clasificadores de fallas en máquinas
#### Temario
* Investigación bibliográfica sobre redes generativas antagónicas
* Definición del caso de estudio de diagnóstico de falla en máquina
* Implementación y programación del modelo generativo en Python
* Entrenamiento de modelos de clasificación solo con datos reales y con datos sintéticos y reales
* Evaluación del desempeño de la estrategia


## 6. Análisis experimental de emisiones acústicas generadas por contacto entre dientes de engranajes (*)
#### Descripción
En las transmisiones por engranajes los dientes están sometidos a diferentes instancias de contacto deslizante y rodante entre ellos. Con el afán de analizar los efectos de estas interacciones en las emisiones acústicas (AE) generadas, previamente se diseñó un banco de ensayos que replica el contacto deslizante-rodante que ocurre entre los dientes. El banco de ensayos deberá ahora ser fabricado, montado, evaluado y puesto en marcha para realizar mediciones de AE en distintas condiciones de carga y velocidad de manera sistemática.
#### Objetivo principal
Implementar y operar un banco de ensayos de dientes de engranaje para análisis de emisiones acústicas
#### Temario
* Fabricación y puesta en marcha del banco de ensayos
* Análisis del contacto entre dientes de engranaje
* Investigación bibliográfica sobre AE y su medición
* Realizar mediciones de AE para distintas condiciones
* Análisis de datos experimentales


## 7. Simulación de las ondas de emisiones acústicas generadas por fricción en ANSYS LS-DYNA (*)
#### Descripción
Las emisiones acústicas (AE) son ondas de esfuerzo elástico de muy alta frecuencia producidas por liberaciones de energía de deformación en sólidos. Una de las principales fuentes de AE en máquinas es la fricción. Debido a que las características de las ondas de AE pueden aportar información respecto del proceso o condición de la máquina, es importante contar con herramientas que permitan conocer mejor su mecanismo de generación. En particular, se desea estudiar el caso del contacto entre un cilindro y una superficie plana mediante simulaciones numéricas en ANSYS LS-DYNA.
#### Objetivo principal
Obtener las formas de onda esperadas de AE para diferentes casos de contacto entre un cilindro y superficie plana mediante simulación numérica.
#### Temario
* Investigación bibliográfica sobre fricción
* Investigación bibliográfica sobre emisiones acústicas
* Aprender a usar el módulo LS-DYNA de ANSYS
* Definir casos de estudio y realizar simulaciones
* Evaluación de resultados obtenidos


## 8. Detección experimental de defectos en estructuras mediante emisiones acústicas
#### Descripción
Las emisiones acústicas (AE) son ondas de esfuerzo elástico de muy alta frecuencia producidas por liberaciones de energía de deformación en sólidos. Al pasar sobre un defecto (grieta, picadura, etc.) durante su propagación, sus características se ven alteradas. El análisis de estas ondas y la determinación de estas alteraciones sirven para la detección de dichos defectos en distintos tipos de estructuras. Además, la combinación de varios sensores puede permitir la localización espacial de dichos defectos.
#### Objetivo principal
Detectar fallas en estructuras simples mediante el análisis experimental de emisiones acústicas.
#### Temario
* Investigación bibliográfica sobre emisiones acústicas
* Investigación bibliográfica sobre técnicas de análisis
* Definir procedimiento experimental y casos de estudio
* Realizar mediciones bajo distinas condiciones
* Analizar las señales medidas según técnicas de la literatura


## 9. Influencia de los recubrimientos de pintura en la medición de emisiones acústicas
#### Descripción
Las emisiones acústicas (AE) son ondas de esfuerzo elástico de muy alta frecuencia producidas por liberaciones de energía de deformación en sólidos. Su correcta medición requiere una preparación de la superficie en donde se ubicará el sensor con el fin de asegurar un buen acople. Esta preparación involucra pulir la superficie del sólido para remover capas de pintura que pudieran afectar la medición. Sin embargo, hay situaciones en donde no es posible remover la capa de pintura por diversas razones. En estos casos, es importante saber cómo afecta la capa de pintura a las señales medidas para no emitir juicios incorrectos respecto de su análisis.
#### Objetivo principal
Determinar la influencia de los parámetros del recubribmiento de pintura en las características de las emisiones acústicas medidas.
#### Temario
* Investigación bibliográfica sobre emisiones acústicas
* Investigación bibliográfica sobre recubrimientos de pintura
* Estudiar relación teórica entre parámetros del recubrimiento y transmisión acústica
* Realizar experimentos bajo distintas condiciones
* Analizar las señales medidas y comparación con la teoría

## 10. Implementación de sistema de medición de ultrasonido de bajo costo
#### Descripción
La inspección no destructiva por ultrasonido consiste en emitir ondas de sonido de alta frecuencia sobre un sólido y medir las reflexiones que se producen por discontonuidades en él. De esta forma, se pueden localizar posibles defectos internos, o bien, realizar otras tareas como medición de espesor o de proximidad a objetos. Hay gran variedad de instrumentos ultrasónicos, por lo que conocer las capacidades y limitaciones de cada uno de ellos es clave a la hora de poder usar la técnica con éxito. Dentro del trabajo, se propone explorar las capacidades de un instrumento de bajo costo que emite y recibe ondas ultrasónicas.
#### Objetivo principal
Caracterizar las capacidades y limitaciones de un transceptor ultrasónico de bajo costo
#### Temario
* Investigación bibliográfica sobre ultrasonido
* Analizar especificaciones de la instrumentación disponible
* Realizar configuración de los instrumentos y conexiones entre ellos
* Desarrollo de scripts para medición y análisis de datos
* Realizar pruebas experimentales bajo condiciones controladas

## 11. Integración de algoritmos y sensores para generación de imágenes acústicas
#### Descripción 
#### Objetivo general 
#### Temario

## 12.Mejoramiento de medición de vibración por video mediante integración con audio
#### Descripción 
#### Objetivo general 
#### Temario

## 13. Granulometría en muestras de rocas mediante imágenes y aprendizaje profundo
#### Descripción 
#### Objetivo general 
#### Temario

## 14. Análisis de emisiones acústicas en componentes impresos en plástico PLA
#### Descripción 
#### Objetivo general 
#### Temario

## 15. Detección de elementos ocultos en muestras de rocas usando magnetometría
#### Descripción 
#### Objetivo general 
#### Temario

## 16. Estudio de lubricación en banco de ensayos de contacto de engranajes (*)
#### Descripción 
#### Objetivo general 
#### Temario

## 17. Emisiones acústicas generadas por distintos materiales bajo carga estática
#### Descripción 
#### Objetivo general 
#### Temario



(*): Temas a desarrollar en el marco de proyecto FONDECYT
