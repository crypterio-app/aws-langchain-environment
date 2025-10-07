<img width="1432" height="924" alt="image" src="https://github.com/user-attachments/assets/4331b682-1155-478f-94d3-7ce5c8e097b1" />


## AWS LangChain | AI Environment 🚀🚀🚀
LangChain is an open-source framework designed to help developers build applications powered by large language models (LLMs) — such as GPT, Claude, or Gemini — that can reason, remember, and interact with external data or systems.

Developing and deploying AI applications, especially those leveraging large language models (LLMs), often require a complex interplay of technologies. This article explores a case study where Ollama, LangChain, Docker, and Kubernetes work together to create a robust and scalable AI solution.


#### 🎯 Main Components:

   - **LLMs & Chat Models**: Interfaces for calling models like OpenAI’s GPT, Anthropic’s Claude, or local models via Ollama.
   - **Prompt Templates**: Helps structure and format dynamic prompts consistently.
   - **Chains**: Sequences of steps that combine prompts, LLM calls, and logic (like “ask the model → process the output → ask again”).
   - **Agents**: LLM-driven systems that can decide which tools to use (like a database or API) to answer a query.
   - **Memory**: Lets your app remember previous interactions for context-aware conversations.
   - **Document Loaders & Retrievers**: Used for connecting LLMs to your documents, databases, or APIs — crucial for RAG (Retrieval-Augmented Generation).
   - **Vector Stores**: Stores document embeddings so the model can “look up” relevant context efficiently (e.g., using FAISS, Chroma, Pinecone).
  

🎯  Key Features
```
✅ Deploy Infrastructure
✅ Launch EC2 Instance
✅ Install Dependencies 
✅ Prepare Kubernetes 
✅ Cluster Post-Configuration
```

🚀 
```
terraform init
terraform validate
terraform plan -var-file="template.tfvars"
terraform apply -var-file="template.tfvars" -auto-approve
```

🧩 Config 

```
scp -i ~/.ssh/<your pem file> <your pem file> ec2-user@<terraform instance public ip>:/home/ec2-user
chmod 400 <your pem file>
```

