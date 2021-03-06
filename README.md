# Computación cuántica para data scientists
¿Que es una computadora cuántica? ¿Para que sirven? ¿Que cosas puedo hacer que no puedo con una computadora clásica?

La idea de este repositorio es responder estas preguntas de forma técnica, práctica y didáctica.
Para entender la estructura de los repositorios, conviene dividirlos en 3 grupos. En primer lugar Notebooks introductorios:


- **1_Introducción a quantum Machine Learning**: Se describe la historia, la motivación matemática y se presentan cualitativamente las ventajas de la computación cuántica. Es el más útil si no se quiere profundizar demasiado en el contenido técnico sino tener una visión más general sobre el tema. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1PmdvN8yNvMZKARUev48Zc5d7Bzrfqqk9?usp=sharing)
- **2_Introducción práctica a la teoría cuántica**: Una introdución matemática y conceptual a los temas más importantes de cuántica, y como se diferencia de teorías clásicas. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1poiAkSd7FsJ9vzaEHHnyHG6nGXlV0eCe?usp=sharing)

En segundo lugar, introducciones a los 2 modelos más populares de computación cuántica:


- **3_Computación cuántica con compuertas (Gate Model)**: El modelo más estudiado en la academia. Es el heredero directo de la computación clásica, ya que trabaja con compuertas lógicas y es fácil de entender. Las ventajas teóricas de este modelo son enormes, pero tiene dificultades técnicas considerables. Aprendemos a entender sus componentes y manejarlas. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1JCHk_YqoiUMSESKzTQtQxxXT4_oCa46Q?usp=sharing)
- **4_Computación adiabática**: El segundo modelo más usado. Es el más usado para resolver problemas de optimización no separables en subrutinas (Max-Cut, traveling salesman, etc). Es dificil de enteder tecnicamente, ya que requiere entender la física subyacente. Es más sencillo para escalear, pero solo sirve para problemas de optimización. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1cH5uTWolLMm16oyLLkG0NvYHbwBYHhkM?usp=sharing)

Finalmente, ejemplos concretos de algoritmos:
- **5_VQE**: Es el método más popular para resolver problemas de optimización en sistemas híbirdos que combinan computadoras del tipo Gate con computadoras clásicas. Se usa para simular sistemas químicos, pero la idea de fondo puede usarse para muchos otros problemas. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1MBGUF_QfI0Ykf2lyWpgewFajrEhPzgxX?usp=sharing)
- **6_Clasificador variacional cuántico**: Clasificadores que se entrenen con data etiquetada. Vamos a reproducir primero la función paridad y usarlo después con la data de Iris. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1ySQx37eSqfTSL9-oRrgGNmFbn5UWLEFI?usp=sharing)
- **7_Métodos de Kernel**: introducimos la versión cuántica de los Kernels, que pueden en principio encontrar patrones más allá de lo clásico. Esta es la base para armar clasificadores del tipo SVM. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/13lbdwJmZFYRghjhEyfPRLk47FvcxTg-C?usp=sharing)
- **8_Quantum CNN**: Usamos circuitos cuánticos variacionales como capas convolucionales para hacer reconomiento de imágenes. Se ve una leve mejora respecto al caso sin la capa cuántica. No es la idea usar circuitos cuánticos realmente (muy costoso), pero es un lindo ejemplo fácil de seguir. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1tXnUFGmGjNgVCrZwzMO_NbGJMcqe9es1?usp=sharing)



![image](quantuminfo.png)
