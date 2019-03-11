## Create Helm chart of product Docker image

Simple helm chart for with webapp.

Build process:

0. Commit code changed
1. Build Java webapp (war)
2. Build docker framework image - test included
3. Add webapp and tomcat to app docker images using docker framework as base - test included
4. Build helm chart
5. Publish to product
