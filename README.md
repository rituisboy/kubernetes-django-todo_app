# kubernetes-django-todo_app
This is a kubernetes project where i deployed a todo app made with django <br>
used deployment,service and ingress in this project <br>
to run this project
`git clone https://github.com/rituisboy/kubernetes-django-todo_app.git`
`kubectl apply -f .\deploy.yaml`
`kubectl apply -f .\service.yaml`
`kubectl apply -f .\ingress.yaml`
and your minikube ip in /etc/hosts file 
`{minikube ip} todo.com`
Now visit todo.com on your local browser the site will be up and running
