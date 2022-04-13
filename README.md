# application-helm
Generic helm chart for all sorts of applications


# versioning 

When updating the repo with a new template or values you must also update the `chart.yaml` file with the next version

`apiVersion: v2
name: application-helm
description: A generic helm chart for all sort of applications
version: {new-version}`

The above will have to be automated as part of the workflow at some point in the future.
