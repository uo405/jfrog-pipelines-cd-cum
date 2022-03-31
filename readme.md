## Overview

This pipeline demonstrates the definition of a simple pipeline that creates and signs a release bundle, and distributes it to an Artifactory edge node. An example Pipelines DSL is used to show how to use integrations, resources, and steps to construct a simple, automated workflow. The pipeline is triggered by any change in any of the BuildInfo resources used to create the release bundle.

This pipeline starts from where the [Pipelines Example: Docker Build and Push](https://www.jfrog.com/confluence/display/JFROG/Pipeline+Example%3A+Docker+Build+and+Push) left off. While that pipeline built and pushed a Docker build, this pipeline takes the Buildinfo from that example and creates the release bundle and distributes it to an edge node.

For instructions on how to run this sample and explanation of configuration, please reference JFrog Pipelines Quickstart documentation: [Pipeline Example: Release to Edge Node](https://www.jfrog.com/confluence/display/JFROG/Pipeline+Example%3A+Release+to+Edge+Node)
