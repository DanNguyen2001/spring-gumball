# CMPE 172 - Lab #10 Notes
**PART 1 (CI)**
**Created Public Repo with gradle workflow**
![image](https://user-images.githubusercontent.com/78176995/235952308-e3288785-7a2e-4426-89ab-0d0db66f81a8.png)

**Commented and pushed to see workflow run in action**
![image](https://user-images.githubusercontent.com/78176995/235952480-9da7518d-263f-465f-86b0-8f77680eea90.png)
![image](https://user-images.githubusercontent.com/78176995/235952720-e84c1fb5-6065-4593-a5b8-8a612744ee4e.png)

**PART 2 (CD)**
**Created Google workflow GCP with the following paramters:
GCP Project:      cmpe172
GKE Cluster Name: cmpe172
GKE Cluster Zone: us-central1-c**
![image](https://user-images.githubusercontent.com/78176995/235953240-d8807bca-74c8-43a1-8060-886ada2ff348.png)

**Created GKE cluster**
![image](https://user-images.githubusercontent.com/78176995/235953307-438134f6-bd87-4a65-bcd7-cac0a01850ce.png)

**Project ID**![image](https://user-images.githubusercontent.com/78176995/235953419-6fd4a40d-688f-4749-ba01-a5ac1b884ebb.png)

**Created Service account**
![image](https://user-images.githubusercontent.com/78176995/235953539-abb016dc-6ad4-42f6-9183-71029e339165.png)

**created Repo secrets**
![image](https://user-images.githubusercontent.com/78176995/235953713-f32350db-351d-4b3f-b3cf-27b8202f3996.png)

**Trigger a CD Deployment by creating a new GitHub Release**![image](https://user-images.githubusercontent.com/78176995/235954051-9948713c-6326-46c0-9c0d-7bb25872d9cd.png)
![image](https://user-images.githubusercontent.com/78176995/235954086-446f90f7-656e-412b-8418-10ea846e82e5.png)
**Deployment is up**
![image](https://user-images.githubusercontent.com/78176995/235954149-4f41480f-1c3c-4794-a672-2224b6f28093.png)
**Service is up**![image](https://user-images.githubusercontent.com/78176995/235954224-0619b867-0f8e-4920-9ffc-b3eb33a548b9.png)
**Creating Jumpbox**
![image](https://user-images.githubusercontent.com/78176995/235954351-69cb79fc-b410-4670-bb51-5ba9d8058aa8.png)
**Jumpbox is up** ![image](https://user-images.githubusercontent.com/78176995/235954445-ce32df07-30d7-40ed-973e-1f047d5ac921.png)
**connect to jumpbox api to check**![image](https://user-images.githubusercontent.com/78176995/235954571-34b303d1-d42d-4d4d-b610-3b758ad7b879.png)
# spring-gumball ci/cd example

### This example demonstrates the following two GitHub Workflows.

* https://help.github.com/actions/language-and-framework-guides/building-and-testing-java-with-gradle

* https://github.com/google-github-actions/setup-gcloud/tree/master/example-workflows/gke

### Build Dependencies

* Gradle 5.6
* JDK 11
