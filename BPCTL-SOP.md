Select your existing application
<img width="1366" height="698" alt="image" src="https://github.com/user-attachments/assets/0f1b8f94-964e-405c-b463-c695c8e5254d" />
add the service that we want to create
<img width="1366" height="698" alt="image" src="https://github.com/user-attachments/assets/c19f515e-edcf-494c-912e-03d19d1e56da" />
give the name of the service 
<img width="1366" height="698" alt="image" src="https://github.com/user-attachments/assets/20d130b0-1979-49db-9eb3-b9edb275d361" />
after save and continue you have to select the enviroments and job template and save and continue
when you choosse the enviroments you have to select the registry and imagename (imagename will be demo-grafana/dev/dev-monitoring )  checks the button for all mannual
disable the push data for insights and then save and continue.
<img width="1366" height="639" alt="image" src="https://github.com/user-attachments/assets/243b63e1-c245-42e5-91a2-97135b1291cf" />
navigate the env deploy detail and select Custom Manifest file/GitOps
<img width="1366" height="639" alt="image" src="https://github.com/user-attachments/assets/c08a4319-7e59-4d0f-b8dd-ae3436b115ac" />
after completeing above steps you will be showing like this
<img width="1366" height="639" alt="image" src="https://github.com/user-attachments/assets/f8afc63c-688d-450f-a2d2-c532aa795a63" />
you have to select image pull policy to always & resource kind selection is not mandotory 
Disable Define Raw Key Value Pairs
enable Validate Deployment Rollout
if you have to deploy the CRD than enable the server side apply otherwise disable it.
<img width="1097" height="453" alt="image" src="https://github.com/user-attachments/assets/697fbfae-1ad5-43f1-9b1e-c3526368d8ed" />
next choose via helm template than select git repo
select the git url and click on load branch 
and select the branch that you want to choose
select Enter File or Folder Path and give the file/folder path
enter the release name 
<img width="1097" height="453" alt="image" src="https://github.com/user-attachments/assets/ae273731-bbd5-4c3f-8146-9f886ebdd9ea" />
* in values file section *
select via git repo 
same as just we do in previous to select and load branch 
and enter the file path including values.yaml
<img width="1130" height="340" alt="image" src="https://github.com/user-attachments/assets/01a3b1e3-559a-4225-b79b-1e101fcd8c7e" />
Disable the prehook and post hook
<img width="1122" height="198" alt="image" src="https://github.com/user-attachments/assets/b54c4e30-75e5-4d74-b3b2-6c8e24efa57f" />
and than save and continue 

