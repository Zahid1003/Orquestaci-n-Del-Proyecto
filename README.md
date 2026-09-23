# El problema de la puerta 1
En respuesta a un incidente interno, la universidad implementó nuevas medidas de seguridad, entre ellas: torres de auxilio, mayor personal de vigilancia y un sistema de escáneres QR en las dos entradas principales del campus. El sistema requiere que cada persona escanee su credencial vigente para ingresar; al hacerlo, se muestra su perfil en una pantalla junto a la entrada.
Sin embargo, se han identificado varias problemáticas:

1.	Registro de ingreso limitado
El sistema permite únicamente un acceso por día. Esto afecta a estudiantes que deben salir y reingresar, ya que al segundo intento aparece el mensaje: “Este QR ya se usó por el día de hoy”. El sistema parece registrar solo la primera entrada, sin contemplar múltiples accesos legítimos.

2.	Vulnerabilidad del escáner QR
Al ser un lector de QR, existe el riesgo de que códigos maliciosos contengan enlaces de descarga de virus o ataques de phishing. Se requiere una contramedida técnica que garantice que solo se acepten códigos generados y validados por la universidad.

3.	Flujo peatonal y riesgos viales
Se instalaron tres escáneres para ingreso, pero solo uno para salida. Además, una de las puertas peatonales fue cerrada, obligando a los estudiantes a cruzar una calle congestionada con vehículos grandes (buses y camiones). Esto genera un riesgo potencial de accidentes por falta de visibilidad y cruces forzados.

4.	Excepciones en el sistema
Los alumnos que ingresan en autobús no necesitan escanear credenciales, lo que genera inconsistencias en el control de acceso.
La universidad habilitó una aplicación móvil para mostrar la credencial en caso de extravío, pero esto puede facilitar vulneraciones si la seguridad solo verifica que se escanee “algo” sin validar su autenticidad.

Enlace de Jira
https://fcaei.atlassian.net/jira/software/projects/IEACFZEZP/boards/4?filter=&groupBy=none

Enlace a overleaf
(En proceso)
