# pim-memorias-tesis
Temas disponibles para Proyectos de Ingeniería Mecánica, Memorias de Título y Tesis de Magíster. Otros temas a convenir. 
Contacto al correo fleaman@udec.cl

## 1. Evaluación de atributos y modelos de aprendizaje automático para detección de falla en engranaje planetario
#### Descripción
El aprendizaje automático ofrece grandes ventajas dentro del análisis de señales para el monitoreo de condición de máquinas. Un punto clave dentro de la construcción de estos modelos es contar con atributos representativos de una falla y que a la vez no sean significativamente influenciados por las condiciones de operación. De esta manera se busca construir modelos lo más general posibles que puedan aplicarse en distintos casos. En el caso a estudiar, se contará con datos previamente medidos de vibraciones y emisiones acústicas en un engranaje planetario medidos a distintas condiciones de operación.
#### Objetivo principal
Evaluar cuantitativamente atributos y modelos de aprendizaje automático aplicados a un engranaje planetario con una falla en el engrane anillo.
#### Temario
* Investigación bibliográfica sobre aprendizaje automático
* Normalización y análisis previo de datos
*	Extracción y cálculo de atributos de las señales
*	Construcción y validación de modelos de clasificación
*	Evaluación cuantitativa de los resultados


## 2. Un método para selección de wavelet madre en el análisis de emisiones acústicas mediante la transformada wavelet
#### Descripción
En el análisis de emisiones acústicas (AE) las herramientas basadas en la transformada wavelet tienen la capacidad de generar mejores resultados que herramientas basadas en la transformada Fourier. Sin embargo, un paso importante dentro de este análisis es la selección de la wavelet madre a utilizar. Esto es clave para obtener resultados satisfactorios, ya que una incorrecta selección de la wavelet madre puede llevar a conclusiones incorrectas. En el trabajo se evaluará un método de selección de wavelet madre basado en fuentes de AE del tipo Hsu-Nielsen.
#### Objetivo principal
Evaluar una propuesta de método para selección de wavelet madre usando datos de AE previamente medidos.
#### Temario
* Investigación bibliográfica sobre AE
* Investigación bibliográfica sobre la transformada wavelet
* Programación del método de selección de wavelet
* Evaluación del método con señales experimentales de AE
* Comparación de resultados con otros métodos


## 3. Concepto de una descomposición modal empírica rápida para el análisis de señales
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


## 4. Implementación de un banco de ensayos para análisis de fricción deslizante y rodante (*)
#### Descripción
En diferentes máquinas y mecanismos los componentes pueden estar sometidos a fricción deslizante o rodante entre ellos. Un ejemplo típico de estos son las transmisiones por engranajes. Con el afán de analizar y medir estas interacciones entre componentes desde el punto de vista tribológico, se propone diseñar un banco de ensayos simple del tipo superficie-cilindro. La idea es que parámetros como velocidades y presiones de contacto se puedan ajustar de una forma controlada con algún mecanismo especial para ello. También se deberá considerar la posibilidad de estudiar la fricción en presencia de lubricación.
#### Objetivo principal
Implementar un banco de ensayos del tipo superficie-cilindro para análisis de fricción rodante y deslizante.
#### Temario
* Análisis de requerimientos del diseño
* Concepto y diseño de detalles del banco de ensayos
* Especificación de componentes y materiales
* Generación de planos para fabricación
* Ensamblaje de componentes para puesta en marcha


## 5. Modelación de emisiones acústicas generadas por fricción deslizante y rodante (*)
#### Descripción
Las emisiones acústicas (AE) son ondas de esfuerzo elástico de muy alta frecuencia producidas por liberaciones de energía de deformación en sólidos. Una fuente importante de AE en máquinas es la fricción. Para el caso de la fricción deslizante entre superficies rugosas, existen algunos modelos que predicen los niveles de AE dados parámetros tales como velocidad de deslizamiento, área y rugosidad. Sin embargo, para el caso de la fricción rodante hay muchos menos estudios al respecto. Un modelo de predicción de niveles de AE para el caso de la fricción rodante puede tener importantes aplicaciones, por ejemplo, en el diagnóstico de condición de rodamientos o engranajes. En este trabajo se propone modelar la AE generada por diferentes casos de contacto entre un cilindro y una superficie plana.
#### Objetivo principal
Modelar los niveles de AE esperados para distintos casos de fricción rodante y deslizante entre un cilindro y superficie plana.
#### Temario
* Investigación bibliográfica sobre fricción
* Investigación bibliográfica sobre emisiones acústicas
* Análisis detallado de modelos existentes para fricción deslizante y rodante
* Adaptar modelos para casos de estudio en particular (cilindro-superficie)
* Evaluación del modelo con datos de la literatura o medidos


## 6. Prototipo de un sistema de medición de vibraciones basado en Raspberry Pi
#### Descripción
En la actualidad existen múltiples sistemas para medición de vibraciones desde aquellos para aplicaciones sencillas hasta aquellos para aplicaciones industriales. Raspberry Pi (en la mayoría de sus versiones) es un microcomputador de bajo costo que cuenta con entradas y salidas digitales para la conexión de sensores y actuadores. Debido a esto, es posible usar esta plataforma para el desarrollo de sistemas de medición de bajo costo combinando hardware y software. Para el caso de las vibraciones mecánicas, se pueden implementar herramientas de análisis y visualización usando el lenguaje Python operando sobre el sistema operativo de Raspberry Pi.
#### Objetivo principal
Desarrollar un prototipo de sistema de medición de vibraciones en la plataforma Raspberry Pi combinando hardware y software.
#### Temario
* Introducción a la plataforma Raspberry Pi
* Implementación de interfaces electrónicas e informáticas
* Programación de herramientas de análisis y visualización
* Comparación con sistema de medición estándar
* Demostración del prototipo en laboratorio

## 7. Modelación de sistemas dinámicos mediante redes neuronales artificiales
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

## 8. Diagnóstico de fallas en máquinas mediante clasificación automática de imágenes tiempo-frecuencia
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

## 9. Generación de datos sintéticos mediante redes generativas antagónicas para el diagnóstico de condición de máquinas
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

## 10. Modelación fenomenológica de las emisiones acústicas generadas en engranajes planetarios.
#### Descripción
Las emisiones acústicas (AE) son ondas de esfuerzo elástico de muy alta frecuencia producidas por liberaciones de energía de deformación en sólidos. Algunas investigaciones han mostrado el gran potencial del análisis de AE para el mantenimiento predictivo de engranajes planetarios. Sin embargo, el estado del arte al respecto es todavía escaso y la mayoría de los estudios son solo análisis experimentales. En este sentido, el contenido frecuencial del espectro de envolvente debe aún ser investigado en detalle para facilitar su interpretación de manera consistente. En el marco de este trabajo, se propone realizar estar investigación utilizando señales simuladas de manera fenomenológica. 
#### Objetivo principal
Establecer una metodología fenomenológica para interpretar el espectro de envolvente de AE medidas en engranajes planetarios.
#### Temario
* Investigación bibliográfica sobre análisis de AE en engranajes planetarios
* Determinar principales factores que influyen en el contenido frecuencial del espectro de envolvente
* Implementar estrategia de modelación fenomenológica de señales de AE en Python 
* Definir casos de estudio y analizarlos mediante la metodología propuesta
* Comparación de la metodología con datos experimentales previamente medidos


## 11. Diseño de un banco de ensayos para análisis del contacto entre dientes de engranajes (*)
#### Descripción
En las transmisiones por engranajes los dientes están sometidos a diferentes instancias de contacto deslizante y rodante entre ellos. Con el afán de analizar y medir estas interacciones desde el punto de vista tribológico, se propone diseñar un banco de ensayos que replique el contacto deslizante-rodante que ocurre entre las superficies de los dientes. La idea es que parámetros como velocidades y presiones de contacto se puedan ajustar de una forma controlada con algún mecanismo especial para ello. También se deberá considerar la posibilidad de estudiar la fricción en presencia de lubricación.
#### Objetivo principal
Diseñar un banco de ensayos consistente en superficies del tipo evolvente en contacto deslizante y rodante.
#### Temario
* Análisis de requerimientos del diseño
* Cálculos geométricos y de accionamiento mecánico
* Concepto y diseño de detalles del banco de ensayos
* Especificación de componentes y materiales
* Generación de planos para fabricación


## 12. Simulación de las ondas de emisiones acústicas generadas por fricción en ANSYS LS-DYNA (*)
#### Descripción
Las emisiones acústicas (AE) son ondas de esfuerzo elástico de muy alta frecuencia producidas por liberaciones de energía de deformación en sólidos. Una de las principales fuentes de AE en máquinas es la fricción. Debido a que las características de las ondas de AE pueden aportar información respecto del proceso o condición de la máquina, es importante contar con herramientas que permitan conocer mejor su mecanismo de generación. En particular, se desea estudiar el caso del contacto entre un cilindro y una superficie plana mediante simulaciones numéricas en ANSYS LS-DYNA.
#### Objetivo principal
Obtener las formas de onda esperadas de AE para diferentes casos de contacto entre un cilindro y superficie plana mediante simulación numérica.
#### Temario
* Investigación bibliográfica sobre fricción
* Investigación bibliográfica sobre emisiones acústicas
* Aprender a usar el módulo LS-DYNA de ANSYS.
* Definir casos de estudio y realizar simulaciones.
* Evaluación de resultados obtenidos.

(*): Temas a desarrollar en el marco de proyecto FONDECYT
