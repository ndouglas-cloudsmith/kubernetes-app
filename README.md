# kubernetes-app
This is purely a test Kubernetes app for educational purposes

```
apiVersion: v1
kind: pod
metadata:
  name: my-html-pod
spec:
  containers:
  - name: my-html-container
    image: docker.cloudsmith.io/acme-corporation/acme-repo-one/my-html-pod:latest
    ports:
    - containerPort: 80
```
