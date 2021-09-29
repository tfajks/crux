crux.yaml is the entry pipeline. You can change it to pick the right version of the framework in resources.
You can also integrate this pipeline with CI/CD

There are a couple of modes of operation:

- on_build_agent - tests will run on a single machine, build agent, use -J properties when selecting this mode, currently Linux Os agents are supported
- on_aks - tests will run on AKS, use -G properties with that option, you need to set valid kubernetes 'k' connection and valid github 'crux' connection for the pipeline
- on_aks_pool_created_for_each_test_run - advanced use, consult documentation
- on_aks_created_for_each_test_run - advanced use, consult documentation