Performance test framework on kubernates

helm repo add https://skckadiyala.github.io/helm-repo/

helm install framework helm-repo/perftest-frmk -n framework

helm install backend nginx-svc --set DNSHostSSL=sslbackend.apicsystest.axwaytest.net --set DNSHost=backend.apicsystest.axwaytest.net -n backend

