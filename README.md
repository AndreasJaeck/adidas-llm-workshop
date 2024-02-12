# Databricks LLM Chatbot Lab

This repository is based on the official [LLM Chatbot Tutorial](https://www.databricks.com/resources/demos/tutorials/data-science-and-ai/lakehouse-ai-deploy-your-llm-chatbot?itm_data=demo_center) and modified to run in a hands on lab envionment with multiple users:



<p align="center">
<img src="https://www.databricks.com/en-website-assets/static/f84979b20d558b0b53d4d3847e0fe578/23744.jpg?raw=true" style="width: 50%"/>
</p>
<hr/>

## For Workshop Participants: 

1. Log into the provided Labs workspace (you should have received an e-mail with credentials)
2. Click on **Workspace** (left side bar)
3. Navigate to **Repos**
4. Pick your **user**
5. Click on the blue **Add** button on the top right corner
6. Pick Repo and paste link of the repository
7. Select "**Create Repo**"
  
## For Admins: 
If you want to setup this hands on tutorial in your own envionment make sure to have the following prerequistes in place:

- Unity Catalog is enabled for your workspace.
- You have access to Foundation Model APIs.
- Vector Index is availabe in your region.
- You have access to Serverless Serving.
- A catalog called **main** with Data Editor permissions for the Participants user group.
- A Service Principal configured in the admin console.
- Access token of the Service Principal stored in the secrets scope **dbdemos** with the key **rag_sp_token**.
- Read Permission on the secrets scope for Service Principal and Participants.

## Author

* [Andreas Jack](https://github.com/AndreasJaeck)

  
  
