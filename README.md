# This project is about deploument of Techchallenge app using Azure CICD in docker container.

- Login to AzureDev hub-  https://dev.azure.com
- Create a project.
- Create Service connections for the project to Azure Resource manager.
- Create Azure repository to store Docker Image. 
- Create project repository and clone the code https://github.com/akibuddinahmed/TechChallengeApp.git 
<img width="1761" alt="image" src="https://user-images.githubusercontent.com/73784434/189929919-43e61c67-b862-4d8d-ab7f-0ad769260476.png">

- Setup the pipeline 
     - Build Docker Image ( This steps requires the dockerfile from the porject ) 
     - Push Docker Image ( This step requires to setup the Azure repository) 
- <img width="1761" alt="image" src="https://user-images.githubusercontent.com/73784434/189930154-cdc0b5af-b13f-4c3b-880e-fb4082a446b2.png">
- Supply the postgres details in `conf.toml` file.
- Run the pipeline
Screenshot 2022-09-13 at 8.23.25 PM<img width="1761" alt="image" src="https://user-images.githubusercontent.com/73784434/189934474-0a6410eb-d427-40a5-9341-f3a848c61908.png">

- Setup an App Service in Azure portal by
 
<img width="1761" alt="image" src="https://user-images.githubusercontent.com/73784434/189933472-1eec7bdf-2df1-4893-b47c-9df369ecc287.png">




