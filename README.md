- Start Minikube
minikube start --extra-config "apiserver.cors-allowed-origins=["http://boot.dev"]"

- Get deployment from the image from bootdotdev online
kubectl create deployment synergychat-web --image=bootdotdev/synergychat-web:latest

