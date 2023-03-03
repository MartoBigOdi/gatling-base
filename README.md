#Repo base para Performance con Gatling 🚀👨🏻‍💻

![img.png](img.png)

#Link de apoyo
https://www.federico-toledo.com/tutorial-de-gatling-en-espanol/

En este Link vas a poder encontrar info sobre Gatling pero no sobre el 
monitoreo que te propongo hacer con grafana, insisto es para tener 
apoyo sobre gatling.

#Commands to run simulations
mvn gatling:test -D gatling.simulationClass=simulations.TestGetAPISimulation

#Para hacer el monitoreo (Grafana) vas a necesitar este repo:
https://github.com/akadzik/gatling-grafana-docker

#Para comenzar con un container desde cero el comando es:
Docker-compose up -d --build

#Para detener el contenedor de Docker que corrimos con Grafana y FluxDB es:
docker-compose stop



