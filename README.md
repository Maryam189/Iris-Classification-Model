# Deploy ML Model in Notebooks by Azure ML Studio

## Steps

1. **Create a machine learning workspace**
2. **Create a new resource group**
3. **Once Deployment is complete, go to resource**
4. **Launch ML Studio**
5. **Create Compute Cluster:** `STANDARD_DS11_V2`
6. **Create Compute Instance:** `STANDARD_DS11_V2`
7. **Clone your git repo in the notebooks tab**
8. **Convert your notebook to a script:**

    ```python
    import mlflow
    mlflow.autolog()
    ```

9. **Register the model by going to the job**
10. **Before Deployment, stop the resources**
11. **Deploy the model:**
    - Use Real Time endpoint wizard
    - For compute, select `Standard_DS1_v2`
12. **Once you deploy, you will get an endpoint.**
