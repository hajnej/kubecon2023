# ArgoCon Europe 2023

## Notes

* Argo Rollouts => blue/green strategy for Web apps ( frontend/UI )
* Implement ArgoCD Preview Diff on the fly 

## Ideas

* Consider to start using ArgoCD ApplicationSets 
* Consider to use GitHub Webhooks to trigger the sync action
* Consider to use Argo Workflows/GHA to automate promotion between environments ( may require to change Adam's opinion about watchdog )

## Obstacles we suffer 

* We aren't Openshift cluster admins ( Argo project tools require CRD to be installed and RBAC set )
* We don't have a deployment pipeline

