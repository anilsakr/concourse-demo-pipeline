# concourse-demo-pipeline
Concourse is a pipeline-based continuous thing-doer.

https://concourse-ci.org/docs.html

1. Install Docker
2. Install Docker compose
3. install fly


fly validate-pipeline --config pipeline.yml
fly format-pipeline --config pipeline.yml
fly -t tutorial set-pipeline -p sample-pipeline -c pipeline.yml
fly -t example pause-pipeline --pipeline my-pipeline
fly -t example unpause-pipeline --pipeline my-pipeline
fly -t example destroy-pipeline --pipeline my-pipeline
fly -t example archive-pipeline -p pipeline-1