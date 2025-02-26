# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

VM 
---------
Pros:
- VMs allow you full access and control of the VM
- Support of both Linux and Windows VMs
- Multiple VMs can be grouped to provide high availability, scalability, and redundancy
- Multiple types to choose from, such as compute or memory-optimized VMs, along with varying amounts of CPU, RAM, and storage
- Lower up front costs compared to purchasing and maintaining hardware

Cons:
- Can be more expensive
- Complexity: setting up and managing VMs are more complex compared to App Service

  

App Service
-------------
Pros:
- Cost Effective for more simple projects
- Easier to deploy:Azure App Service simplifies the deployment process. You can easily deploy and manage your applications using tools like Visual Studio and Azure DevOps.
- High availability, auto-scaling, and support of both Linux and Windows environments
- Support of multiple languages, such as .NET, .NET Core, Java, Ruby, Node.js, PHP, or Python
- Scaling: Vertical or Horizontal scaling. Vertical scaling increases or decreases resources allocated to our App Service, such as the amount of vCPUs or RAM, by changing the App Service pricing tier. Horizontal scaling increases or decreases the number of Virtual Machine instances our App Service is running

Cons:
- Limited Customization: App Service may not offer the same level of customization as VMs.
- Dependency on Platform: You are dependent on the platform's updates and changes. If Azure makes changes to the App Service platform, it could impact your application


Choice: App Service


Justification: or this project, which was aimed at getting familiar with deploying applications, I chose to use Azure App Service due to its ease of deployment and cost-effectiveness. Given that the project was a simple learning exercise with only myself working on the app, there was no need for multiple virtual machines to accommodate multiple users. Additionally, Azure App Service seamlessly integrates with GitHub and supports Python code, making it an ideal choice for our requirements. 




### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 








