# Chicken-Disease-Classification-Using-MLOPS-DVC-Pipeline-



# Workflow
    
1. Update config.yaml
2. Update secrets.yaml [Optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline
8. Update the main.py
9. Update the dvc.yaml


Azure: 

Registry name : chickenapp
Login server : chickenapp.azurecr.io

Password : dwTTszYPDlufGBxLTtsC/m+VvExiRVKWz6dG6e+/62+ACRDtZgo2



AZURE-CICD-Deployment-with-Github-Actions
Save pass:
s3cEZKH5yytiVnJ3h+eI3qhhzf9q1vNwEi6+q+WGdd+ACRCZ7JD6

Run from terminal:
docker build -t chickenapp.azurecr.io/chickenapp:latest .

docker login chickenapp.azurecr.io

docker push chickenapp.azurecr.io/chicken:latest

