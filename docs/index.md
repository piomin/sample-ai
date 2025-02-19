# AI Software Template

This application, sample-ai, is created from an AI Software Template. These software templates create a new source code repository as well as a new GitOps deployment repository.

The chosen sample source applicable is included in the source code repository.

## Sample Source Application

RAG (Retrieval Augmented Generation) streamlit chat application with a vector database. Upload a file containing relevant information to train the model for more accurate responses.

## Repositories

The source code for your application can be found in [https://github.com/piomin/sample-ai ](https://github.com/piomin/sample-ai ).
 
The GitOps repository, which contains the Kubernetes manifests for the application can be found in 
[https://github.com/piomin/sample-ai-gitops ](https://github.com/piomin/sample-ai-gitops ). 

## Application namespaces 

The default application is found in the namespace: **`rhdh-app`**. Applications can be deployed into their own unique namespace or multiple software templates can generate numerous applications into the same namespace.