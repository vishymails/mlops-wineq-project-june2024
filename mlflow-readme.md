# Clone my github repo 





# Start mlflow server

```
mlflow server --backend-store-uri sqlite:///mlflow.db --default-artifact-root ./artifacts --host 127.0.0.1 -p 1234

```



# Go to mlflow Ui 

```
http://localhost:1234
```

# Run experiments with 3 variations 

```
dvc repro
```
Note : 3 times execution with different values 



