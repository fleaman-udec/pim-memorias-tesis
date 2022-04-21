# pim-memorias-tesis
Temas disponibles para Proyectos de Ingeniería Mecánica y Memorias de Título. Contacto fleaman@udec.cl

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


## 4. Diseño de un banco de ensayos para análisis de fricción deslizante y rodante
#### Descripción
En diferentes máquinas y mecanismos los componentes pueden estar sometidos a fricción deslizante o rodante entre ellos. Un ejemplo típico de estos son las transmisiones por engranajes. Con el afán de analizar y medir estas interacciones entre componentes desde el punto de vista tribológico, se propone diseñar un banco de ensayos simple del tipo superficie-cilindro. La idea es que parámetros como velocidades y presiones de contacto se puedan ajustar de una forma controlada con algún mecanismo especial para ello. También se deberá considerar la posibilidad de estudiar la fricción en presencia de lubricación.
#### Objetivo principal
Realizar el diseño (básico y detalles) de un banco de ensayos del tipo superficie-cilindro para análisis de fricción rodante y deslizante.
#### Temario
* Análisis de requerimientos del diseño
* Concepto y diseño básico del banco de ensayos
* Diseño en detalles del banco de ensayos
* Especificación de componentes y materiales
* Generación de planos para fabricación


## 5. Modelación de emisiones acústicas generadas por fricción rodante
#### Descripción
Las emisiones acústicas (AE) son ondas de esfuerzo elástico producidas por liberaciones de energía de deformación en sólidos. Algunas de las fuentes de AE en componentes mecánicos son los impactos, la fricción y la deformación plástica, entre otras. Para el caso de la fricción deslizante entre superficies rugosas, existen algunos modelos que predicen los niveles de AE dados parámetros tales como velocidad de deslizamiento, área y rugosidad. Sin embargo, para el caso de la fricción rodante hay muchos menos estudios al respecto. Un modelo de predicción de niveles de AE para el caso de la fricción rodante puede tener importantes aplicaciones, por ejemplo, en el diagnóstico de condición de rodamientos o engranajes.
#### Objetivo principal
Proponer un modelo para estimar el nivel de AE generado por fricción rodante para un caso en particular.
#### Temario
* Investigación bibliográfica sobre fricción
* Investigación bibliográfica sobre emisiones acústicas
* Análisis detallado del modelo para fricción deslizante
* Propuesta de un modelo para fricción rodante
* Evaluación del modelo con datos de la literatura


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
