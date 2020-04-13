# MANUAL
1. operator-sdk new bookstore-operator-helm --api-version=david.com/v1alpha1 --kind=BookStore --type=helm --helm-chart helm-charts/book-store 
2. operator-sdk build davidmachacek/bookstore-operator-helm:latest
3. docker push davidmachacek/bookstore-operator-helm
