# trabajofinal2 - kubernetes
--levanta las contraseñas 
kubectl apply -f secrets.yaml
--crea el servicio posgres, tulizando volumenes
kubectl create -f  postgres.yml
--configra el ngnix
sudo docker build -t coderjourney/mealplan-frontend:1.0.0 .
--levanta el servicio fronted con una imagen de otro proyecto
kubectl create -f frontend.yml 

