# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

### Assess app changes that would change your decision.

## Comparison

## Azure Virtual Machines (VMs)

# Advantages:

Full Control: I have complete control over the operating system, configurations, and installed software.
Flexibility: I can run any application regardless of its programming language, framework, or technology stack.
Custom Configurations: Ideal for applications requiring custom configurations or software.

# Disadvantages:

Management Overhead: Requires more hands-on management, including OS updates, security patches, and software maintenance.
Potentially Higher Costs: Managing VMs can be more expensive due to the need for infrastructure engineers.

## Azure App Service

# Advantages:

Simplified Management: Azure handles the underlying infrastructure, allowing me to focus on my application.
Scalability: Easily scale my application up or down based on demand.
Integrated Services: Built-in support for CI/CD, authentication, and monitoring.

# Disadvantages:

Less Control: Limited control over the underlying environment compared to VMs.
Potentially Higher Costs for High-Performance Apps: Can be more expensive for high-performance applications.


## Decission

For deploying my FlaskWebProject, I used Azure App Service. Here’s why:

Ease of Management: I can focus on developing my application without worrying about infrastructure management.
Scalability: Easily scale my application based on traffic and demand.
Integrated Features: Benefit from built-in CI/CD, authentication, and monitoring services.