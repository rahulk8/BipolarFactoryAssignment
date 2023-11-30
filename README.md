This a Simple Web application using lightweight Kubernetes k3

Configuration & Setup steps are as below : 
1. Here I have provisioned two EC2 Instances i.e. app server & dev server
   
![image](https://github.com/rahulk8/BipolarFactoryAssignment/assets/37226415/12696526-ccef-4cea-851a-b498052a74a9)

2. Have configured CI/CD platform like Jenkins
   
![image](https://github.com/rahulk8/BipolarFactoryAssignment/assets/37226415/1eaea1a7-41b9-45bb-9652-2bf550ab3b86)

3. Have successfully configured Kubernetes K3 for managing containerized application

![image](https://github.com/rahulk8/BipolarFactoryAssignment/assets/37226415/db9b3de9-69f6-4079-880f-15a1b2195540)

4. Configuring Github Webhook to automatically trigger a build on every push to main branch

![image](https://github.com/rahulk8/BipolarFactoryAssignment/assets/37226415/9840564b-cf45-4311-b3cd-96c709e9bfb4)

5. App is successfully tested & TestNg Report is successfully generated in the Jenkins workspace

![image](https://github.com/rahulk8/BipolarFactoryAssignment/assets/37226415/ade3a154-b24b-43d5-be22-595f1235f418)

6. Web application successfully deployed on app server & running on port 8082 in aws

![image](https://github.com/rahulk8/BipolarFactoryAssignment/assets/37226415/d06391f2-330d-44b7-b987-d754aee12a12)

7. Node Exporter is successfully configured & running on port 9100 on app-server which we have to monitor
![image](https://github.com/rahulk8/BipolarFactoryAssignment/assets/37226415/0940494a-a7db-45f9-9990-1a68177a1ee2)

8. Metrics is also accessible under node exporter

![image](https://github.com/rahulk8/BipolarFactoryAssignment/assets/37226415/023b3aed-ba35-4cbd-9b56-6119496744e4)

9. C-advisor is successfully up & running on port 8084 on app server

![image](https://github.com/rahulk8/BipolarFactoryAssignment/assets/37226415/7a049032-83b7-4d79-932d-0c7db55741d5)

10.Prometheus is successfully configured & running on port 9090 on dev server

![image](https://github.com/rahulk8/BipolarFactoryAssignment/assets/37226415/01b20c42-1055-4ccf-8f39-f28ab595721a)

11. Prometheus as target is successfully configured on dev server

![image](https://github.com/rahulk8/BipolarFactoryAssignment/assets/37226415/a9f98e90-a2a9-4704-9b41-ee9290338508)

12. C-advisor , node exporter & Prometheus as target is successfully configured , up &  running  on dev server

![image](https://github.com/rahulk8/BipolarFactoryAssignment/assets/37226415/2d7293af-4fac-4b03-981c-30174749bfe5)

13. Successfully configured Grafana on port 3000 on dev server 

![image](https://github.com/rahulk8/BipolarFactoryAssignment/assets/37226415/0773f639-637a-424a-a2b2-b8c565085e44)

14 . Configuring Prometheus server URL under Grafana on dev server

![image](https://github.com/rahulk8/BipolarFactoryAssignment/assets/37226415/eeba31eb-8755-4212-826f-d3dc7ff8b1ad)


15. Copying Kubernetes nodes dashboard ID for visualing a dashboard in grafana from grafana.com/grafana/dashboards

![image](https://github.com/rahulk8/BipolarFactoryAssignment/assets/37226415/96601b7a-d6d6-4f23-a1aa-9c6472d54e00)

16. Successfully imported & visualized dashboard in grafana

![image](https://github.com/rahulk8/BipolarFactoryAssignment/assets/37226415/7a05dabe-8bbf-4d30-932d-c4252b691c08)

17. Creating alert rule

![image](https://github.com/rahulk8/BipolarFactoryAssignment/assets/37226415/9cc8cf31-6542-4c9d-b077-9f999c1211ae)

18. Setting alert rule name

![image](https://github.com/rahulk8/BipolarFactoryAssignment/assets/37226415/045a7ac7-33d0-4db9-ba98-e551775c2a68)

19. Alert created successfully

![image](https://github.com/rahulk8/BipolarFactoryAssignment/assets/37226415/90bdc1cd-ee64-4cca-98ae-be53d6d2d449)

20. Alert is firing successfully

![image](https://github.com/rahulk8/BipolarFactoryAssignment/assets/37226415/7e73bf03-040d-44cc-a03e-0df187f21dbd)

21. Configuring Notification policies here

![image](https://github.com/rahulk8/BipolarFactoryAssignment/assets/37226415/92c1e043-64b4-4e55-ac5b-49b850f5907c)

22 . Configuring Contact points to get alert on email

![image](https://github.com/rahulk8/BipolarFactoryAssignment/assets/37226415/18042bfb-1517-4fbb-a5ec-761fa05c8598)


