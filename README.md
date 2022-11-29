# CMPE 172 - Lab #10 Notes

### CD Workflow (PART 1)

Gradle Build Screenshots

<img width="1440" alt="Screenshot 2022-11-28 at 8 15 33 PM" src="https://user-images.githubusercontent.com/87669072/204437435-58b479e2-8858-4845-8cbd-6d62de951cde.png">

<img width="1440" alt="Screenshot 2022-11-28 at 8 17 16 PM" src="https://user-images.githubusercontent.com/87669072/204437645-a97904e1-1458-4a52-bd97-4318b4b83701.png">

### CD Workflow (PART 2)

Service account details retreived by going to service accounts on google cloud

<img width="1440" alt="Screenshot 2022-11-28 at 9 03 13 PM" src="https://user-images.githubusercontent.com/87669072/204443286-069b6784-1f6c-4be6-aa21-efc0ebaca9b6.png">

Granting permissions
<img width="1440" alt="Screenshot 2022-11-28 at 9 07 56 PM" src="https://user-images.githubusercontent.com/87669072/204443823-d7dcde44-d8f6-4cfe-be7e-313f6d445ff3.png">

Creating action secrets in github repository by going to settings and scrolling down to action secrets then creating it following the lab guide. project ID was given by the project ID in the account and creating a JSON key gave the service account JSON.

<img width="1440" alt="Screenshot 2022-11-28 at 9 03 30 PM" src="https://user-images.githubusercontent.com/87669072/204443320-fce547db-f50b-461c-a148-fa8a3c659055.png">

Creating a Github release in the repository

<img width="1440" alt="Screenshot 2022-11-28 at 9 19 59 PM" src="https://user-images.githubusercontent.com/87669072/204445319-26d68918-c04e-43ee-ba4c-336c30e0534f.png">

Running cluster in Google Kubernetes

<img width="1440" alt="Screenshot 2022-11-28 at 9 22 49 PM" src="https://user-images.githubusercontent.com/87669072/204445655-7da7b054-b5fa-4ecc-9e5c-1bf5b334f0fc.png">

Successful deployment in the github actions

<img width="1440" alt="Screenshot 2022-11-28 at 9 22 19 PM" src="https://user-images.githubusercontent.com/87669072/204445580-3a950949-8325-4e79-af51-d47a3f5af172.png">

Service shown working in the Service and Ingress tab on google kubernetes

<img width="1440" alt="Screenshot 2022-11-28 at 9 23 32 PM" src="https://user-images.githubusercontent.com/87669072/204445756-94c44444-93be-4f8c-9a0a-2f1384ab97ac.png">

Creating spring-gumball-lb with create ingress

<img width="1440" alt="Screenshot 2022-11-28 at 9 24 42 PM" src="https://user-images.githubusercontent.com/87669072/204445921-e2b846e2-b56d-4a24-82bd-5e4f77e44050.png">

Load balancer working after creating the ingress

<img width="1440" alt="Screenshot 2022-11-28 at 9 32 41 PM" src="https://user-images.githubusercontent.com/87669072/204447021-98f0f365-2317-471c-afd0-3fe5bb9fb520.png">

Gumball on GKE using the service node to access the website address

<img width="1440" alt="Screenshot 2022-11-28 at 9 33 42 PM" src="https://user-images.githubusercontent.com/87669072/204447177-d099acd1-0919-4217-a2fa-132a5ab87247.png">

