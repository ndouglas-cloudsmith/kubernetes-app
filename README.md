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

<img width="1492" height="813" alt="Screenshot 2025-07-28 at 22 21 19" src="https://github.com/user-attachments/assets/8505577c-e38c-4fe2-a9a9-9e53c7163460" />

<img width="1231" height="368" alt="Screenshot 2025-07-28 at 22 24 54" src="https://github.com/user-attachments/assets/c1954cd6-25d3-4de9-af09-f511c5ab9890" />
