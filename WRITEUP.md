# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

For both a VM or App Service solution for the CMS app:

### Analyze costs:

- VM: Virtual Machines typically incur higher costs due to the need for managing and maintaining the underlying infrastructure, including OS updates, security patches, and scaling resources manually.

- App Service: App Services generally offer a more cost-effective solution with a pay-as-you-go model, automatic scaling, and reduced operational overhead.

### Analyze scalability:

- VM: Scaling with VMs requires manual intervention to add or remove instances, which can be time-consuming and less responsive to sudden traffic spikes.

- App Service: App Services provide automatic scaling capabilities, allowing the application to handle varying traffic loads seamlessly without manual intervention.

### Analyze availability:

- VM: Ensuring high availability with VMs involves setting up and managing multiple instances, load balancers, and failover mechanisms, which can be complex and resource-intensive.

- App Service: App Services offer built-in high availability and disaster recovery options, ensuring consistent uptime and reliability with minimal configuration.

### Analyze workflow:

- VM: Managing VMs involves more complex workflows, including infrastructure management, OS maintenance, and manual scaling, which can slow down development and deployment processes.

-App Service: App Services streamline workflows with integrated development tools, continuous deployment options, and simplified management and enhancing productivity.

### Choose the appropriate solution (VM or App Service) for deploying the app:

I developed a web app instead of a virtual machine because it offers better scalability and cost-efficiency for our CMS application.

### Justify your choice:

App Services provide automatic scaling, high availability, and simplified workflow management, which are crucial for handling varying traffic loads and ensuring consistent performance. Additionally, the reduced operational overhead and integrated development tools make App Services a more suitable choice for our deployment needs.

### Assess app changes that would change your decision:

If the application required more granular control over the infrastructure, such as specific OS configurations, custom networking setups, or specialized security requirements, a VM might become the preferred option. In such a scenario, the app and its dependencies would need to be adapted to leverage the flexibility and control offered by VMs, including managing OS-level configurations and ensuring robust security measures.
