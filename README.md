A collection of architectural decision records from the book Microservices Up & Running. These decision records use [Michael Nygard's LADR format](http://thinkrelevance.com/blog/2011/11/15/documenting-architecture-decisions)

## Operating Model
* [OPM-1: Decision tracking](https://github.com/implementing-microservices/ADRs/blob/master/OPM-1-Decision-Tracking.md)
* [OPM-2: Limit Team Size](OPM-2-Limit-Team-Size.md)
* [OPM-3: Define Team Principles](OPM-3-Team-Principles.md)
* [OPM-4: Team Design Phase](OPM-4-Team-Design-Phase.md)
* [OPM-5: Microservice Ownership](OPM-5-Microservice-Ownership.md)


## Infrastructure
* [INF-1: Infrastructure as code](INF1-infrastructure-as-code.md)
* [INF-2: Use Terraform for Infrastructure Changes](INF2-Use-Terraform.md)
* [INF-3: Use a CICD Pipeline for Infrastructure Changes](INF3-CICD-Infrastructure.md)
* [INF-4: Use Github Actions for CI/CD Pipelines](INF4-Github-Actions-CICD.md)
* [INF-5: Use Github for Code Management](INF5-Use-Github.md)
* [INF-6: Host Microservices in AWS](INF6-Use-AWS.md)
* [INF-7: One Repository Per Environment](INF7-One-Repo-Per-Env.md)
* [INF-8: Use a Managed Kubernetes Service](INF8-Use-EKS.md)
* [INF-9: Deploy Microservices Using a GitOps Deployment Tool](INF9-Use-GitOps-Tool.md)
* [INF-10: Implement a Traefik Ingress Controller](INF10-Trafek-Ingress.md)
* [INF-11: Use Shared and Managed Database Services](INF11-Use-Shared-Managed-DB.md)


## Microservice Design
* [MSD-1: Use Standard Design Process](MSD-1-Use-Standard-Design-Process.md)
* [MSD-2: Scope Design Using Key Actors](MSD-2-Scope-Design-Using-Key-Actors.md)
* [MSD-3: Use Jobs as the Unit of Analysis](MSD-3-Use-Jobs-For-Analysis.md)
* [MSD-4: Use the Standard Job Story Format](MSD-4-Use-Job-Story-Format.md)
* [MSD-5: Use PlantUML to Discover Interaction Patterns](MSD-5-Use-PlantUML.md)
* [MSD-6: Seperate Service Endpoints into Commands and Queries](MSD-6-Seperate-Commands-Queries.md)
* [MSD-7: Colect Feedback on your Service Designs](MSD-7-Collect-Feedback.md)
* [MSD-8: Web APIs are Layered on Top of Microservices](MSD-8-Web-APIs-On-Top.md)
* [MSD-9: Use Event Storming Instead of Formal DDD](MSD-9-Use-Event-Storming.md)
* [MSD-10: Microservices Can Share Physical Database Clusters](MSD-10-Share-DB-Clusters.md)

## Microservice Engineering
* [MSE-1: Avoid Microservices Calling Each Other Directly ](MSE1-Intra-MS-Comms.md)
* [MSE-2: Use Redis to Implement the Reservations Database](MSE2-Redis-For-Reservations.md)
* [MSE-3: Start Microservices with Reusable Templates](MSE3-Start-With-Templates.md)
* [MSE-4: Starting Microservices from Reusable Templates](MSE4-Healthcheck-Template.md)
* [MSE-5: Use Faux Git Submodules](MSE5-Faux-Git-Submodules.md)



