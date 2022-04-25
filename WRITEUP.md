# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

I chose app service since it may be a little bit lower compare to virtual machine. App service doesn't require much maintenance, so choosing it will help save a lot of time and money, unlike using VM that needs a lot of maintenance and security configuration. The app service is much quicker to create and deploy. It is exceptionally simple for my workflow to push my changes to GitHub Repo. Both App Service and Virtual Machine has the same availability, but there might be some risk base on the user configuration, so base on my research I think the app service is more reliable when it comes to setting up and running the app, the app is pretty small, so it will be easy to scale up in the future at lower cost. After comparing the availability, scalabity, costs, and workflow, i decided to use app service to implement my project.

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

Azure Virtual Machine is an IaaS or Infrastructure-as-a-Service, If the application is much conplex than this, maybe has more dependencies and functionalities that need much maintenance I would consider adopting VM if i want to get full control over the application management and deployment, also VM will give me more control over and access to configuration assets, because i am looking for a way to handle all operations. Moreover if i need to configure high security on the app, VM would be the best choice compare to App Service. 
