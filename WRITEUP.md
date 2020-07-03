# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs*
App Service's B1 instance is free for 1st month where as VM was costing more than 1,000+ INR/Month

*scalability*
Its easy to scale up App Service by changing the pricing tier of the App Service plan where as for VM to scale we may need to deploy, set and manage additional resources like RAM, GPU, Storage etc

*availability*
Both App Service and VM have high availabilty and different regions are also available to deploy the app

*workflow*
Its easy to automate the workflow in App Service using Kudu

- I have used App service to deploy the app as it is fast, easy and cost effective for a python flask app. There was no need to setup and install dependencies in a VM before deploying the app. With just VM tool, I was able to deploy entire app on Web service easily.

### Assess app changes that would change your decision.

Would have needed to select and start entire VM. Next step could been to install the dependencies, setup flask and modify port numbers with firewall secuirty.  
