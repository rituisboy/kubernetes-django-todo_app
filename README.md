


# kubernetes-django-todo_app

This is a Kubernetes project where I deployed a todo app made with Django.

To run this project:

1. Clone the repository:

```bash
git clone https://github.com/rituisboy/kubernetes-django-todo_app.git
```

2. Apply the Kubernetes resources:

```bash
kubectl apply -f deploy.yaml
kubectl apply -f service.yaml
kubectl apply -f ingress.yaml
```

3. Add your Minikube IP to the `/etc/hosts` file:

```bash
<minikube ip> todo.com
```

4. Visit `todo.com` on your local browser, and the site will be up and running.


Remember to replace `<minikube ip>` with the actual IP address of your Minikube instance.
