# Processes and Tools

## Processes

Processes that define how software is developed and deliverd are more important than tools.

After developing a process that fits your individual requirements and basic conditions, __you can choose the tools that best implement your process__.

Processes are ven more important when addressing the interactions between different departments. A handover of artifacts for delivery must be defined. __It's important to install interdisciplinary experts__ in the interface of both Developmend and Operations.

We want to accomplish the following:

* Aligning __responsibilities with artifacts not with roles__ (traditional approach).
* Setting up streamlining of __holistic process__ that maintains speed while Development hands off software to Operations.
* Including Development and Operations in a __comprehensive end-to-end delivery process__.
* Including Operations in Agile frameworks and processes, such as Scrum and Kanban.

Development and Operations share the same processes, and both groups are focused on delivering application changes to the user at a high frequency and quality. The __unified process emphasizes the cycle time and prefers the vertical optimization approach__.

According to this method, every application is created and executed on the architecture that is perfect for this concrete application. The individual __components of the infrastructure are laid out to fulfill the requirements for the specific application__. Optimization across the borders of individual applications is rare or does not occur at all.

Traditionally, the vertical optimization approach is preferred by Developemtn team. In DevOps, both Development and Operations __prefer workable solutions in production and are open-minded about optimizing vertically__.

## Tools

Processes are more important than tools, but __tools are still important, specially for automating activities__ along the delivery process. The more tools you have in your tool kit, the better you can decide which tool is the best fit for a given task.

Streamlining __DevOps is heavy reliant on end-to-end automation__:

* Building
* Unit testing
* Acceptance testing
* Deploying services
* Configuration options (target environments)

With tools like Puppet or Chef, domain-specific languages (DSL) can be used to describe the attributes of the environments (e.g, technical users, permissions, and installed packages). Code and scripts are stored in version control systems.

This approach has many benefits:

* Abstracted descriptions of machines by using DSL while enjoying full power of scripting languages.
* Declarative descriptions of target behavior.
* Management of code and infrastructure in version control systems.
* Synchronization of environments by automatic provisioning.
* Complete setups, including virtualizations, can be managed automatically.
* Sharing scripts (e.g, Puppet manifest) allows cross-functional team and different parties to use those scripts to set up their respective environments.
