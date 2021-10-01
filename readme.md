1) docker build -t elainecro/conversao-temperatura:v1 .
2) docker push elainecro/conversao-temperatura:v1
3) docker tag elainecro/conversao-temperatura:v1 elainecro/conversao-temperatura:latest
4) docker push elainecro/conversao-temperatura:latest
5) kind create cluster --name clusterconversao --config cluster.yaml
6) kubectl apply -f deployment.yaml