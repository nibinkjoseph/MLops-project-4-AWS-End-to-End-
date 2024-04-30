# MLops-project-AWS-End-to-End

Amazon sagemaker pipeline

* CI/CD service for machine learning
* Automate, create, and manage end to end ML workflows
* Visualize and manage the workflow using amazon sagemaker studio
* We can reuse the template for any use case.
* Manage different version of the same model
* Model registry we can track the versions in a central repository
* Choose the right model for deployment based on the business requirement
* Sagemaker logs every step of the workflow
* Audit traills can be used to recreate models

SageMaker Pipelines

Step1 : Sagemaker
We need to create a domain for sagemaker studio
Click domains under Admin configuration
![image](https://github.com/nibinkjoseph/MLops-project-4-AWS-End-to-End-/assets/63180074/2db8d7c0-bf54-4d4d-bf81-43381606db69)

Go for Quickset up
![image](https://github.com/nibinkjoseph/MLops-project-4-AWS-End-to-End-/assets/63180074/b6d82bd9-85b0-4c34-9f5b-f17fc9aa73f8)

![image](https://github.com/nibinkjoseph/MLops-project-4-AWS-End-to-End-/assets/63180074/8fc99e6f-3367-44dd-a36e-3d4c8757b629)

Step 2; Go to Notebook and select Notebook instances
![image](https://github.com/nibinkjoseph/MLops-project-4-AWS-End-to-End-/assets/63180074/c4e8b9c0-f665-46a1-9c2e-06d79f56be7b)

Notebook instance name: mlops-predict  
Create an IAM role  
![image](https://github.com/nibinkjoseph/MLops-project-4-AWS-End-to-End-/assets/63180074/83bb5b2f-2b33-436c-8e04-aad50ee51546)
![image](https://github.com/nibinkjoseph/MLops-project-4-AWS-End-to-End-/assets/63180074/7ced52a3-3e40-48b3-99e2-2651847a3b80)

Notebook instance is created
![image](https://github.com/nibinkjoseph/MLops-project-4-AWS-End-to-End-/assets/63180074/fddc3196-19e4-43b6-81ce-dcd91cf5bafc)
