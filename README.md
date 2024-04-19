# Deteccion-objeto-cv2
Identifica los objetos en el rango visual con nombre, fecha, hora y lugar (Practica Python).
## Identificar objetos con características especificas.
Desarrollar la lógica a ser ejecutada.
Buscar un modelo pre-entrenado y probarlo.
Identificar los objetos en un espacio especifico.
Validar e imprimir las características solicitadas.
### Carga un archivo para definir la arquitectura de la red neuronal MobileNetSSD.
`	prototxt = "MobileNetSSD_deploy.prototxt.txt" `
### Carga los pesos pre-entrenados de la red neuronal MobileNetSSD
`	model = "MobileNetSSD_deploy.caffemodel" `
### Carga la arquitectura de la red neuronal y los pesos pre-entrenados, creando así un modelo de red neuronal para su uso en detección de objetos con OpenCV.
`	net = cv2.dnn.readNetFromCaffe(prototxt, model) `
### Inicializa la captura de video desde la cámara web predeterminada.
`	cap = cv2.VideoCapture(0) `
### Esta función cierra todas las ventanas creadas por OpenCV.
`	cv2.destroyAllWindows() `
	
