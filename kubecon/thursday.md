# Thursday

##  [Unlocking Argo CD’s Hidden Tools for Chaos Engineering - Featuring VCluster and More](https://kccnceu2023.sched.com/event/1Hybl/unlocking-argo-cds-hidden-tools-for-chaos-engineering-featuring-vcluster-and-more-dan-garfield-brandon-phillips-codefresh)

Hidden Tools = undocumented

What kind problem we suffer?

* Slow recon time
* Template rendering times increase
* Web UI unresponsive

**Intro to Gen Resources**

* https://github.com/argoproj/argo-cd/tree/master/hack

It creates Clusters, Apps, Projects, Repos.

**DEMO**

* Generate samples => go build -o ../argocd-generator

* argocd-autopilot

* https://codefresh.io/blog/a-comprehensive-overview-of-argo-cd-architectures-2023/
* GitOps Certification ( MELOVECHAOS, MESLOWCHAOS )

##  [Tips from the Trenches: GitOps at Adobe](https://sched.co/1Hyca)

* Use Crossplane instead of Terraform or... use Terraform to create management cluster and then use Crossplane / ClusterAPI

## [Ephemeral Clusters as a Service with ClusterAPI and GitOps](https://sched.co/1HyXe)

* Tech stack = AKS, Argo, ExternalDNS, CertManager, LGTM, Kyverno, ClusterAPI
* GitHub repo: https://github.com/joaquinrz/capi-gitops