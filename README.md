#  Optimización Dinámica de Rutas con Aprendizaje por Refuerzo (RL) en Colombia

Este repositorio contiene un cuaderno de Google Colab que simula un entorno de distribución logística en Colombia. A través de un agente inteligente basado en **Q-Learning**, se busca optimizar las rutas de transporte desde una ciudad depósito (Bogotá) hacia otras ciudades destino, **minimizando las distancias** mediante Aprendizaje por Refuerzo.

---

##  Objetivo

- Aplicar Aprendizaje por Refuerzo (Q-Learning) en el contexto del ruteo logístico.
- Usar datos simulados de ciudades reales de Colombia para entrenamiento.
- Visualizar los nodos en un mapa interactivo.
- Obtener una ruta sugerida eficiente desde el punto central de despacho.

---

##  Datos incluidos

- `nodos_colombia_ruteo.csv`: contiene la lista de ciudades, sus coordenadas geográficas y demanda.
- `matriz_distancias_colombia.csv`: matriz de distancias entre las ciudades calculadas con la fórmula de Haversine.

---

##  ¿Qué es el Aprendizaje por Refuerzo?

El **Aprendizaje por Refuerzo (RL)** es un paradigma de aprendizaje automático donde un agente toma decisiones en un entorno para maximizar una recompensa acumulada. En este cuaderno se usa:

- **Estados**: cada ciudad
- **Acciones**: moverse a otra ciudad no visitada
- **Recompensa**: negativa a la distancia (menor es mejor)
- **Q-Learning**: algoritmo de RL basado en tablas

---

##  ¿Cómo usar este cuaderno?

1. **Abrir el cuaderno en Google Colab**:
    [Abrir en Colab](https://colab.research.google.com/github/tuusuario/RL_Rutas_Colombia/blob/main/Aprendizaje_Refuerzo_Rutas_Colombia.ipynb)

2. **Subir los archivos CSV incluidos** (`nodos_colombia_ruteo.csv`, `matriz_distancias_colombia.csv`).

3. **Ejecutar paso a paso**:
   - Visualizar el mapa de ciudades
   - Entrenar el agente con Q-Learning
   - Visualizar la tabla Q y la ruta sugerida

---

##  Resultados esperados

- Mapa interactivo de ciudades y nodos logísticos.
- Tabla Q aprendida con valores de utilidad por transición.
- Ruta óptima recomendada desde el punto central (Bogotá).

---

##  Créditos

Desarrollado por **Cristian Alejandro Zafra Rodríguez**  
Docente e investigador en Ingeniería Industrial  
Universidad Antonio Nariño  
 Enfoque en rutas inteligentes, modelos RL aplicados a logística y transporte, y sistemas de toma de decisiones.

---

##  Licencia

Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.

