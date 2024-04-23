# Setting up IBM Code Engine

## Install Code Engine plugin

``` sh
ibmcloud plugin install code-engine
```

## Create Code Engine project

``` sh
ibmcloud ce project create --name project-one
```

## Create Code Engine application from local code (Buildpack strategy)

``` sh
ibmcloud ce app create --name project-one --build-source . --strategy buildpacks
```