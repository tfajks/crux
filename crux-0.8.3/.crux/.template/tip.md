crux.template.yaml contains advanced user configuration of the pipeline, you can change things such as:

- docker image for JMeter containers 
- HELM chart for deployments with AKS
- memory settings
- timeouts
- replace implementations of some steps with your own
- insert additional pipeline steps

stop.crux.tests.yanl can be used to stop already running tests if they went south
