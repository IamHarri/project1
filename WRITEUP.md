# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
+ Cost: App service is cheaper than VM in general. One limitation of App Service is always paying for the service plan.
+ Scalability and availability: App service is more scalability and availability, easy to config this feature. Virtual Machine should be grouped to provide high availability, scalability.
+ Workflow: Compare to VM, App Service has a shorter workflow. We just need to choose the support language on App Service and config the source code for it to deploy. On the other side, VM need to create a VM, then run the command to deploy App Service.


- *Choose the appropriate solution (VM or App Service) for deploying the app*
In this case, I choose App service for deploying the CMS app. I just deploy this app for severals hours so App service is more suitable, also saving the cost. 

- *Justify your choice*
The CMS works well with my option. The workflow for deployment the app is simple. The only limittation with this option is  it needs longer time for deployment

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 
If the requirement is deploy this app for a long time, source code for the apps quite complicated (need more RAM, CPU), or the languague is not supported by the App service, Virtual machine should be my option. Morerover, if the app need to ssh to the machine to debug something related network it is also the VM.