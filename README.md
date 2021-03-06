# GoCD-issh
## Getting Started With GoCD (thoughtworks)
### https://www.gocd.org/getting-started/part-1/

- learning about some of GoCD's concepts and features, and trying them out on a real server.
- If you haven't installed GoCD yet, please download GoCD. You can view the GoCD Installation Guide to install the GoCD Server and at least one GoCD Agent
- (Server defaults to: http://localhost:8153) after setup

Creating a Pipeline
- A pipeline, in GoCD, is a representation of workflow or a part of a workflow. For instance, if you are trying to automatically run tests, build an installer and then deploy an application to a test environment, then those steps can be modeled as a pipeline.
- Another equally important concept is that of a material. A material is a cause for a pipeline to "trigger" or to start doing what it is configured to do. Typically, a material is a source control repository (like Git, Subversion, etc)
- A pipeline needs to have at least one material and can have as many materials of different kinds as you want.
- The concept of a pipeline is extremely central to Continuous Delivery. Together with the concepts of stages, jobs and tasks, GoCD provides important modeling blocks which allow you to build up very complex workflows, and get feedback quicker.
