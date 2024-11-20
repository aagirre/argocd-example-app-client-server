# argocd-example-app-client-server
Tiene dos apps, un cliente que ofrece un endpoint y un servidor que permite hacer un curl

app cliente servidor funcionando Submariner:
kubectl exec test-client-6d4bbfc58d-rr92f -- curl -s http://242.0.1.253:8080
o bien
kubectl exec test-client-6d4bbfc58d-rr92f -- curl -s http://test-server.default.svc.clusterset.local:8080

app cliente servidor sin funcionar Submariner:
kubectl exec test-client-6d4bbfc58d-6n8tn -- curl -s http://10.98.72.136:8080
