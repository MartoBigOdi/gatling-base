#Repo base para Performance 🚀👨🏻‍💻

# gatling-framework
gatling framework for perfomance and stress testing

#Commands to run simulations
mvn gatling:test -D gatling.simulationClass=simulations.TestGetAPISimulation

#Para comenzar con un container desde cero el comando es:
Docker-compose up -d --build

#Para detener el contenedor de Docker que corrimos con Grafana y FluxDB es:
docker-compose stop



