# protobootapplmh

# Taller de CI/CD

# Luis Miguel Hurtado Cova

## •	La URL del repositorio donde se guarda el código de la Proof of Concept (PoC).

https://github.com/luishurtado15/protobootapplmh/tree/master

## •	Las URLs de los entornos donde se despliega la Proof of Concept (PoC).

### DEV

http://protoboardapplmh-env.eba-tpfcjbpj.us-east-1.elasticbeanstalk.com/
<div align="left"><img src="./images/image43.png" width="500"/></div>

### PDN

http://protoboardapplmh-prod.eba-tpfcjbpj.us-east-1.elasticbeanstalk.com/
<div align="left"><img src="./images/image25.png" width="500"/></div>

## •	Capturas de pantalla de los entornos de montaje de los pipelines donde se vea claramente la identificación de la cuenta de usuario y/o del entorno de CI, las fases y demás datos que se consideren relevantes de los pipelines o procesos implementados.

## 1.	CI CON GITHUB ACTIONS


•	Repositorio git:

https://github.com/luishurtado15/protobootapplmh

•	Proyecto descargado en local utilizando el IDE Intellij

<div align="left"><img src="./images/image1.png" width="500"/></div>


•	Archivo maven.yml
<div align="left"><img src="./images/image2.png" width="500"/></div>

•	Pruebas en CI/CD

•	Exitoso
<div align="left"><img src="./images/image3.png" width="500"/></div>

<div align="left"><img src="./images/image4.png" width="500"/></div>


•	Fallar pruebas unitarias
<div align="left"><img src="./images/image5.png" width="500"/></div>

<div align="left"><img src="./images/image6.png" width="500"/></div>

<div align="left"><img src="./images/image7.png" width="500"/></div>

•	Fallar pruebas de integración

<div align="left"><img src="./images/image8.png" width="500"/></div>

<div align="left"><img src="./images/image9.png" width="500"/></div>

•	Cambiar parámetros en el checkstyle
<div align="left"><img src="./images/image10.png" width="500"/></div>

•	Cambiar el threshold (COVEREDRATIO) de JaCoCo.

<div align="left"><img src="./images/image11.png" width="500"/></div>
<div align="left"><img src="./images/image12.png" width="500"/></div>


## 2.	CI CON JENKINS
      
•	Exitoso

<div align="left"><img src="./images/image13.png" width="500"/></div>


•	Fallar pruebas unitarias

<div align="left"><img src="./images/image14.png" width="500"/></div>

<div align="left"><img src="./images/image15.png" width="500"/></div>


•	Fallar pruebas de integración

<div align="left"><img src="./images/image16.png" width="500"/></div>

<div align="left"><img src="./images/image17.png" width="500"/></div>


•	Cambiar el threshold (COVEREDRATIO) de JaCoCo

<div align="left"><img src="./images/image18.png" width="500"/></div>

<div align="left"><img src="./images/image19.png" width="500"/></div>


•	Cambiar parametro del checkstyle
<div align="left"><img src="./images/image20.png" width="500"/></div>


•	Visualizar con Blue Ocen

<div align="left"><img src="./images/image21.png" width="500"/></div>

<div align="left"><img src="./images/image22.png" width="500"/></div>

<div align="left"><img src="./images/image23.png" width="500"/></div>


## 3.	CI/CD con AWS
 •	Despliegue con el pipeline exitoso
<div align="left"><img src="./images/image24.png" width="500"/></div>

<div align="left"><img src="./images/image25.png" width="500"/></div>

<div align="left"><img src="./images/image42.png" width="500"/></div>

•	Fallo de pruebas unitarias
<div align="left"><img src="./images/image26.png" width="500"/></div>

<div align="left"><img src="./images/image27.png" width="500"/></div>

•	Fallo de pruebas de integración
<div align="left"><img src="./images/image28.png" width="500"/></div>


•	Cambiar parametró de Jacoco

<div align="left"><img src="./images/image29.png" width="500"/></div>

•	Cambiar Parametro del CheckStyle
<div align="left"><img src="./images/image30.png" width="500"/></div>


•	URL actuator/info
<div align="left"><img src="./images/image31.png" width="500"/></div>

•	URL actuator/health
<div align="left"><img src="./images/image32.png" width="500"/></div>


•	URL actuactor/metrics
<div align="left"><img src="./images/image33.png" width="500"/></div>


•	URL actuator/beans
<div align="left"><img src="./images/image34.png" width="500"/></div>

Cloudwatch


•	Logs de codebuild

<div align="left"><img src="./images/image35.png" width="500"/></div>

<div align="left"><img src="./images/image36.png" width="500"/></div>


•	Métricas de servicios
<div align="left"><img src="./images/image37.png" width="500"/></div>



•	Reportes de CodeBuild
Test Unit
<div align="left"><img src="./images/image38.png" width="500"/></div>
<div align="left"><img src="./images/image39.png" width="500"/></div>


Jacoco Report
<div align="left"><img src="./images/image40.png" width="500"/></div>

<div align="left"><img src="./images/image41.png" width="500"/></div>


# MUCHAS GRACIAS

# INTEGRACIÓN Y ENTREGA CONTINUA DE SOFTWARE
# EAFIT - 2024
