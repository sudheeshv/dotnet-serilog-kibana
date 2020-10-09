# dotnet-serilog-kibana
Logging with ElasticSearch, Kibana, ASP.NET Core and Docker


# step one
goto \src\ElasticKIbanaDocker folder and run
docker-compose up -d

verify kibana and elastic serarch services are running 

elasticsearch : http://localhost:9200/
kibana : http://localhost:5601/

# step two
run the solution and goto http://localhost:5601/ portal and create index under management > kibana > index patterns 




