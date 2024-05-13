Prometheus---->servicemonitor--->service--->pod

1.create a deployment for application
2.create service to expose the application
3.create servicemonitor by mentioning namespaces and service to be monitored 
4.inject prometheus spec in helm values to find the servicemonitor by mentioning servicemonitorselector 
