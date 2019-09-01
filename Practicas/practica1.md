# Seguridad y privacidad en Redes

## Práctica 1 - Introducción

### 1. ¿Cuál es la diferencia entre seguridad y privacidad?

- **Seguridad:** Proteger la información y los sistemas de información de los accesos, uso, divulgación, interrupción, modificación o destrucción no autorizados.

- **Privacidad:** No revelar información o revelar selectivamente de manera de protegerla de una posible intromisión.

### 2. Defina y relacione los conceptos de vulnerabilidad, amenaza e incidente.

- **Vulnerabilidad:** Es una debilidad o fallo en un activo.

- **Amenaza:** Es violación potencial de la seguridad. Las amenazas sacan ventaja de las vulnerabilidades. Una amenaza no solamente puede restringirse a una amenaza informática; pueden haber amenazas naturales como terremotos, incendios, inundaciones.
Una amenaza atenta contra la confidencialidad, integridad y disponibilidad de la información.
Son causadas por fallas humanas, ataques malintencionados, catástrofes naturales.

- **Incidente (de seguridad):** Es un evento adverso que afecta los activos de la organización. Se produce cuando una amenaza se concreta. Todo incidente detectado debe ser reportado a quien corresponda.

Ejemplos de incidentes:
- Defacement
- Acceso no autorizado
- Robo de contraseñas y/o información
- Ataque de DDoS


### 3. ¿A qué se hace referencia con el concepto de “seguridad en capas”?

Desde la capa mas exterior a la mas interna:

`Comunicaciones -> Sistema operativo -> Base de datos -> Aplicativo`

### 4. ¿A que se llama ingeniería social? De un ejemplo de ingeniería social en Internet y otro que no implique el uso de una computadora/smartphone/tablet.

>Es un conjunto de trucos, engaños o artimañas que permiten confundir a una persona para que entregue información confidencial.

Un ejemplo de ingeniería social en internet es el phishing.
Que no implique el uso de una computadora o similar, "el cuento del tío".

### 5. Identifique algún incidente de seguridad de la información de público conocimiento. Cual fue el bien afectado. Que error permitió el problema. Que se podría haber realizado para evitar el problema.

Recientemente, se ha filtrado mas de 700GB de información sensible de la Policía Federal y de la Policía de La Ciudad. El caso conocido como GorraLeaks se produjo mediante un phishing.

>Los hackeos se habrían llevado a cabo mediante un correo electrónico que simulaba ser de la superintendencia de Bienestar, “el cual contenía un link que al ser accionado redireccionaba a un formulario en el que solicitaba que se completen datos personales e inclusive datos de usuario y contraseña de cada afiliado”, según relató ante la justicia un subcomisario de la División Investigaciones de Delitos Tecnológicos de la PFA.

>La información filtrada abarca alrededor de 5GB de audios con escuchas telefónicas y una base de datos con 200.000 PDFs que contienen información personal de agentes policiales (nombre y apellido, DNI, teléfono fijo y móvil, estado civil, edad, mail, domicilio, dependencia, cargo, situación de actividad y número de legajo).

[Fuente](https://www.losandes.com.ar/article/view?slug=el-hacker-que-ataco-a-la-policia-federal-viralizo-una-foto-de-patricia-bullrich)

### 6. Analice riesgos introducidos en una organización por el uso de redes sociales y mensajería instantánea.

Puede haber filtrado de información confidencial. Riesgo de phishing, ramsomware.

### 7. ¿Qué medidas de seguridad adopta en los siguientes casos:

Se listan algunas cuestiones relacionadas con la seguridad.

- **Cuando uso una computadora de la Sala de PC de la Facultad.** Iniciar en sesión privada.
- **Cuando me inscribo a rendir un final a través del sistema SIU Guaraní.** Que el sitio SIU no tenga errores del certificado SSL.
- **En el uso del teléfono celular.** No instalar aplicaciones poco confiables. Restringir el acceso a los dispositivos de hardware a las aplicaciones solo lo necesario.
- **Cuando me conecto a una red inalámbrica.** Si es pública (sin contraseña) usar una VPN.
- **Cuando me solicitan información personal en una llamada telefónica.** No dar información o asegurarse que quién llama sea alguien que realmente necesite los datos.
- **Cuando me solicitan información personal en un correo electrónico.** Ignorar el e-mail.
- **Cuando camina por la calle, respecto a sus pertenencias personales.**
- **En el cajero automático.** 
- **Cuando interactúa con un sitio de Internet para acceder a cuentas personales y para realizar compras en linea (mercadolibre o con tarjeta de crédito)** Que el sitio tenga un certificado válido.

### 8. Los siguientes términos,referencian distintos tipos de ataques o problemas de seguridad. Indique en cuáles de estos se necesita SÍ o SÍ de la ingeniería social para que el ataque o problema se pueda concretar de forma exitosa:

| Exploit 	| Malware      	| Cracking   	| Phishing      	|
|---------	|--------------	|------------	|---------------	|
| MITM    	| Fuerza bruta 	| Sextorsión 	| Cripto Mining 	|
| Baiting 	| Tailgating   	| Ransomware 	| Vishing       	|


- Baiting
- Sextorsion
- Ransomware?
- Vishing (combinación de las palabras «voz» y “phishing”.)
- Tailgating


### 9. Enumere que información confidencial se vería expuesta en caso de perder su celular u otro dispositivo móvil si no se hubieran adoptado medidas de prevención adecuadas.

Hoy en día, un teléfono celular contiene gran parte de información referida a nuestro día a día, nuestras finanzas, relaciones, agendas, trabajo, etc.

Si no se adoptan medidas para proteger la privacidad, la pérdida de un teléfono móvil de un individuo puede comprometer seriamente su privacidad e información al tener información sobre su vida, finanzas, etc.

### 10. Suponiendo que usted pierde (o le roban) su notebook y/o su celular:
1. **¿Qué medidas podría haber adoptado para evitar la pérdida de confidencialidad de la información?**

En el caso de un teléfono celular: usar bloqueos biométricos o patrones que impidan que puedan acceder a la información. (Cifrar la tarjeta SD, algunos móviles lo permiten).

Una notebook, proteger el acceso con contraseña, cifrar el /home con una clave segura. Usar booteo seguro.

2. **¿Qué medidas podría haber adoptado para evitar la pérdida de disponibilidad de la información?**

Sincronizar con algún sitio en la nube para poder rápidamente disponer de la información que se encontraba en el dispositivo perdido/robado.

### 11. Pruebe en una máquina virtual con Linux y luego en otra con Window, el acceso físico al sistema suponiendo el desconocimiento de las contraseñas de acceso.

Si montamos los discos en otro equipo. Tanto en Windows como en Linux si las particiones no están cifradas se pueden acceder a los datos.