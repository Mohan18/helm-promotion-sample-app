# Example of Helm application for multiple environments

This is single application that has different configurations for 3 different environments

#Adding new line for test

* For the [QA](values-qa.yaml) environment
* For the [Staging](values-staging.yaml) environment
* For the [Production](values-prod.yaml) environment

The repository also contains several Codefresh pipelines

* [Build only pipeline](pipelines/0_build_only.yml)
* [Basic deployment](pipelines/1_basic_deploy.yml)
* [Environment Board](pipelines/2_environment_board.yml)
* [Manual approval](pipelines/3_approval.yml)
* [Staging deployment](pipelines/4a_staging.yml)
* [Production deployment](pipelines/4b_production.yml)

See the [documentation page](https://codefresh.io/docs/docs/ci-cd-guides/environment-deployments/) for more details.

