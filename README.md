<h1 style="color:red;">
Este proyecto fue desarollado en otro repositorio. Si desea mas informacion sobre el ver el siguiente enlace:
<a href="https://gitlab.com/saualopez/arcodex">link </a>
</h1>




# ARCODEX

Nuestro proyecto más destacado es el Automatic Respiration Control Device , el EX es por todos los estudiantes externos.
Es un prototipo de ambu automatico que apoya a ventilar a los pacientes en casos de emergencia.
EL prototipo trata de mitigar uno de los problemas mas graves de la mayoria de prototipos que existen en linea, es la de tener un sistemas de control
de lazo cerrado para el control de la presion y flujo de aire al paciente.

## SENSORES

Se tienen pruebas con los siguientes sensores
### Sensores de Flujo:
		- YF-S201: un sensor diseñado para medir el flujo de agua, pero posiblemente adaptable
		para medir el flujo de aire en el sistema de respiracion.
### Sensores de presion:
		- ADP1101: un sensor de caracteristicas medicas, que trabaja en el rango adeacuado para medir las presiones
		de un sistema de ventiacion. Es especificamente para medir la presion en el sistema.

		- MPS2017: un sensor de tambien de caracteristicas medica, que trabaja de forma identica que el ADP1101.

		- MPX10DP: Un sensor de presion diferencial, para utilizar el principio de Bernoulli, en un tubo de Venturi.
		Y calcular el flujo de aire dentro del sistema.
		Trabaja en el rango de presion de un sistema de ventilacion, por lo que lo hace el indicado.

		- MPX5500DP: Sensor diferencial, que utiliza el mismo principio del MPX10DP pero en un rango de presion mucho mas
		grande por lo que no es el ideal a utilizar.
## CIRCUITO DEL SISTEMA DE VENTILACION

El circuito del sistema de ventilacion esta formado de la siguiente forma:

		
	SALIDA AMBU --> SENSOR DE FLUJO/CAUDAL --> SENSOR DE PRESION --> SALIDA
				^			^
				|			|
				|			|
                    Hay dos opciones:           ADP1101
			-El sensor de YF-S201	        MPS2017
			-O por meddio de un sensor
			diferencial.			
			
## 3D-DESING-STL

Se diseño varias partes no solo para el comportamiento mecanico, si no tambien para el circuito del sistema de ventilacion.Entre ellas:
	
		-Codo, al cual entra un tubo PVC de 1/2", tiene una salida para una manguera de 3mm que va a un sensor de presion y una salida que seria la salida del circuito del ventilador.
		
		-Venturi, un tubo venturi con entrada y salida de tubo PVC 1/2".Y las salidas para el sensor diferencial, por medio de salidas a manguera de 3mm.

		-Reductor de salida Ambu convencional hacia un tubo PVC 1/2"

		-Reductor de tubo PVC 1/2" a salida de maguera de 3mm.
