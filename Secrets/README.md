# Commands

- kubectl create secret generic db-secret --from-literal=DB_Host=sql01 --from-literal=DB_User=root --from-literal=DB_Password=password123 -o yaml


kubectl create secret generic \
app-secret --from-literal=DB_Host=mysql
--from-literal=DB_User=root


kubectl create secret generic \
app-secret --from-file=app_secret.properties
--from-literal=DB_Password=paswrd
