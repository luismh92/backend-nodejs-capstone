# Deployment

#### Create the deployment using the following command and your deployment file:
`kubectl apply -f deploymongo.yml `

#### kubectl get deployments
`kubectl get deployments`

#### Delete deployment
`kubectl delete deployment secondchanceapp`

#### Build image for Dockerfile
`docker build . -t us.icr.io/$MY_NAMESPACE/secondchanceapp`

#### Push the image to the container regis
`docker push us.icr.io/$MY_NAMESPACE/secondchanceapp`