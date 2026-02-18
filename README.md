# Control de Vehículo mediante Gestos de Mano  
# Hand Gesture Controlled Vehicle

## 📌 Descripción | Description
Proyecto de visión artificial que permite controlar un vehículo mediante el reconocimiento de gestos de la mano en tiempo real, utilizando una cámara como interfaz de entrada. El sistema traduce los gestos detectados en comandos de control para el movimiento del vehículo.

Computer vision project that allows controlling a vehicle through real-time hand gesture recognition using a camera as the input interface. Detected gestures are translated into control commands for vehicle movement.

---

## 🎯 Objetivo | Objective
Diseñar e implementar una interfaz humano-máquina natural, basada en visión artificial, aplicada al control de un sistema móvil.

Design and implement a natural human-machine interface based on computer vision applied to mobile system control.

---

## 🧠 Arquitectura del Sistema | System Architecture

1. Captura de video en tiempo real  
2. Procesamiento de imagen y preprocesamiento  
3. Detección de mano y reconocimiento de gestos  
4. Generación de comandos de control  
5. Ejecución de comandos en el vehículo  

> El sistema está diseñado para operar con baja latencia, permitiendo un control fluido y responsivo.

---

## 🛠 Tecnologías Utilizadas | Technologies Used
- Python  
- OpenCV  
- Procesamiento de imagen en tiempo real  
- Control de motores  

---

## ⚙️ Funcionamiento | System Operation
- La cámara captura continuamente el entorno del usuario.
- Se identifican regiones de interés correspondientes a la mano.
- Los gestos son clasificados según su forma y movimiento.
- Cada gesto se mapea a un comando específico (avance, retroceso, giro, detención).
- El vehículo ejecuta el comando recibido.

---

## 📈 Resultados | Results
- Reconocimiento estable de gestos en tiempo real  
- Control fluido del vehículo  
- Baja latencia entre detección y respuesta  
- Sistema robusto ante variaciones moderadas de iluminación  

---

## 🚀 Posibles Mejoras | Future Improvements
- Implementación de modelos de aprendizaje profundo para clasificación de gestos  
- Mejora en la robustez ante condiciones de iluminación adversas  
- Integración con comunicación inalámbrica bidireccional  
- Optimización del procesamiento para hardware embebido  

---

## 👤 Autor | Author
Francisco Ponce  
Electronic Civil Engineer
