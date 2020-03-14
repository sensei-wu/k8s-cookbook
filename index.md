# Services
## Expose a service quickly
`kubectl expose rc kubia --type=LoadBalancer --name kubia-http`
# Inside the container
## Execute a command 
`kubectl exec kubia-7nog1 -- curl -s http://10.111.249.153`
