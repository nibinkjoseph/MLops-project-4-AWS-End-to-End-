# AWS-End-to-End Mlops Project to Predict Abalone Age using Amazon Sagemaker

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

# SageMaker Pipelines

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

Step 3 : Go back to the domain page
![image](https://github.com/nibinkjoseph/MLops-project-4-AWS-End-to-End-/assets/63180074/b4a26785-4293-4b50-b85c-dba3ea55a659)

From instance page click on to studio option
![image](https://github.com/nibinkjoseph/MLops-project-4-AWS-End-to-End-/assets/63180074/d44a5ae4-6555-415a-a603-988e61db0c29)

Open Jupyter 
![image](https://github.com/nibinkjoseph/MLops-project-4-AWS-End-to-End-/assets/63180074/2e4503d8-fc92-4855-9535-bfa0a8625801)

Upload the files to Jupyter
![image](https://github.com/nibinkjoseph/MLops-project-4-AWS-End-to-End-/assets/63180074/562c33e3-c0e5-4f3d-90d7-346af6136d76)

Go to Sagemaker studio

Click deployment and select projects
![image](https://github.com/nibinkjoseph/MLops-project-4-AWS-End-to-End-/assets/63180074/53c2d858-6dc7-4bc0-ba76-49f21158ca92)
    + Create project
    + Select a template
    + Select model building, training, and deployment
![image](https://github.com/nibinkjoseph/MLops-project-4-AWS-End-to-End-/assets/63180074/61c6aceb-293c-43fd-a2ca-530747ac36e2)

Search for codecommit and open it. You will notice two repositories
![image](https://github.com/nibinkjoseph/MLops-project-4-AWS-End-to-End-/assets/63180074/335632d4-7902-469d-930e-961422dc8a32)


Select Studio Classic

![image](https://github.com/nibinkjoseph/MLops-project-4-AWS-End-to-End-/assets/63180074/94e6c0d4-1ffb-4248-8da5-c833316a7bab)


Name : my-space
![image](https://github.com/nibinkjoseph/MLops-project-4-AWS-End-to-End-/assets/63180074/f0c3f80e-c12f-42d3-b2cd-a8f957dd42a5)

Next page
![image](https://github.com/nibinkjoseph/MLops-project-4-AWS-End-to-End-/assets/63180074/cbb408a8-d44c-4741-a48c-b94fbb6c1a84)

Create a project
Name:mlopsjan24
![image](https://github.com/nibinkjoseph/MLops-project-4-AWS-End-to-End-/assets/63180074/b6ef5ebd-9f62-4d8c-91f4-c56d22b4c929)

![image](https://github.com/nibinkjoseph/MLops-project-4-AWS-End-to-End-/assets/63180074/debab87a-6237-42c0-9630-7c320491c90a)


Go to pipeline and double click


Clone the repository
![image](https://github.com/nibinkjoseph/MLops-project-4-AWS-End-to-End-/assets/63180074/e7b7d59d-ba68-4cd3-92e8-20e74535db03)



Model registry
![image](https://github.com/nibinkjoseph/MLops-project-4-AWS-End-to-End-/assets/63180074/247f3701-5457-44d2-a9b9-9ef9a102a93d)

![image](https://github.com/nibinkjoseph/MLops-project-4-AWS-End-to-End-/assets/63180074/86f53c52-4983-4ca9-b97a-b26007ab692a)

![image](https://github.com/nibinkjoseph/MLops-project-4-AWS-End-to-End-/assets/63180074/475f69bc-2b1e-46c6-8a19-df0c3bf26c1f)

![image](https://github.com/nibinkjoseph/MLops-project-4-AWS-End-to-End-/assets/63180074/d033d639-1f72-47f1-ab9b-76cc82c4ad9b)

![image](https://github.com/nibinkjoseph/MLops-project-4-AWS-End-to-End-/assets/63180074/a03cb536-8dca-46b9-83e3-0d30c94da0e9)

![image](https://github.com/nibinkjoseph/MLops-project-4-AWS-End-to-End-/assets/63180074/d97746eb-f3a9-4859-ae2c-df42c9017845)


![image](https://github.com/nibinkjoseph/MLops-project-4-AWS-End-to-End-/assets/63180074/3bff7ee4-4e98-43c5-82ba-5eee6783631d)

![image](https://github.com/nibinkjoseph/MLops-project-4-AWS-End-to-End-/assets/63180074/0aa354f6-3d98-4db0-bb9c-8c99aac3586e)

![image](https://github.com/nibinkjoseph/MLops-project-4-AWS-End-to-End-/assets/63180074/b31557de-bde6-42cb-be1a-f7dcc357eed8)





