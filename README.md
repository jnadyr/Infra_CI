# Project Summary
Infrastructure as Code project to assist the CI/CD Load Testing Course
✔️ Techniques and technologies used
The following techniques and technologies are explored in this App:
Creating machines to run Docker containers: automatic creation of machines by AWS ECS (Elastic Container Service) powered by Fargate.
Using modules: Utilizing Terraform modules developed by providers and the community.
Environment separation: 2 separate environments automatically built by Terraform, reusing code.
📁 Accessing the project
You can download the zip file of the base project or access the source code of the final project.
🛠️ Opening and running the project
The project was developed in VS Code (Visual Studio Code). Therefore, install VS Code (it can be a recent version) and, on the home screen, look for the extensions option, or press Ctrl+Shift+X, and search for HashiCorp Terraform. This will give us intellisense support, making the code writing process faster.
If you downloaded the zip file, extract the project before browsing for it, as it cannot be opened directly from a zip file.
Go to the directory and open the project folder. After opening the project, open a terminal (it can be the one integrated with VS Code), navigate to the env/Homolog folder, and run the terraform init command inside it. Now Terraform is initialized and we can start using it. To create the infrastructure, run terraform apply in the Production folders (env/Homolog).
🏆
Gostaria de fazer algum ajuste na nomenclatura dos termos técnicos ou precisa de ajuda para traduzir o restante do arquivo?
