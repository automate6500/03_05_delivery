# 03_05_delivery
This repo is for the delivery workflow.

# REQUIREMENTS
1. In the second repo, add the exercise files and then create a workflow using the starter workflow for *Publish Docker Container*.  Update the workflow to call the integration workflow.

    Additionally, add permissions for the integration workflow.  After the `uses` block, add:

        permissions:
          contents: read

1. Add a job to build and publish the code as a container image once the integration tests are complete.

    This requirement is partially completed in the previous step by adding the starter workflow.

    However, the workflow still needs to be modified so the build and publish steps run _after_ the integration tests.
