# kubernetes-django-todo_app
This is a kubernetes project where i deployed a todo app made with django <br>
used deployment,service and ingress in this project <br>
to run this project <br>
`git clone https://github.com/rituisboy/kubernetes-django-todo_app.git` <br>
`kubectl apply -f .\deploy.yaml`<br>
`kubectl apply -f .\service.yaml`<br>
`kubectl apply -f .\ingress.yaml`<br>
and your minikube ip in /etc/hosts file <br>
`{minikube ip} todo.com`<br>
Now visit todo.com on your local browser the site will be up and running
