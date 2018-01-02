# R on Azure

Development of data science and AI becomes easier than ever before thanks to cloud computing. The Github repo site collects a set of R packages, tools, and case-studies for doing R data science on Azure cloud. 

These packages and tools are categoried into four groups, representing four typical tasks data scientists or AI developers may frequently work on. 

Category|Features
----------------------|-----------------------------------------------------------------------------------------------------
[Cloud resource operation and administration](https://github.com/yueguoguo/r-on-azure#cloud-resource-operation-and-administration)|Simplify the way to interact with Azure cloud platform and operate resouces on Azure for various tasks.
[Scalable and advanced analytics](https://github.com/yueguoguo/r-on-azure#scalable-and-advanced-analytics)|Enable large-scale and parallel data analytics in R environment.
[Remote interaction and access to Cloud instance](https://github.com/yueguoguo/r-on-azure#interaction-and-remote-access)|Enhance work efficiency on cloud for R based analytics. 
 [Application and service deployment](https://github.com/yueguoguo/r-on-azure#application-and-service-deployment)|Make operationalizing solution and deploying it as service easy.

## Cloud resource operation and administration
R packages and tools in this category are featured by offering a simplified way to interact with Azure cloud platform and operate resouces (e.g., blob storage, Data Science Virtual Machine, Azure Batch Service, etc.) on Azure for various tasks. 

* [AzureSMR](https://github.com/Microsoft/AzureSMR)<sup>[P]</sup><sup>[T]</sup> - R package for managing a selection of Azure resources. Targeted at Data Scientists who need to control Azure Resources without needing to both Administrators. APIs include Storage Blobs, HDInsight(Nodes, Hive, Spark), ARM, VMs.
* [AzureDSVM](https://github.com/Azure/AzureDSVM) - R package that offers convenient harness of Azure DSVM, remote execution of scalable and elastic data science work, and monitoring of on-demand resource consumption.
* [doAzureParallel](https://github.com/Azure/doAzureParallel) - R package that allows users to submit parallel workloads in Azure.
* [rAzureBatch](https://github.com/Azure/rAzureBatch) - a HTTP proxy library written in R for Azure.
* [AzureML](https://github.com/RevolutionAnalytics/AzureML) - an R interface to [AzureML](https://studio.azureml.net/) experiments, datasets, and web services.

## Scalable and advanced analytics
R packages and tools in this category allow one to performan large-scale R-based analytics on cloud with the bleeding-edge frameworks such as Spark, Hadoop, Microsoft Cognitive Toolkit, Tensorflow, Keras, etc. 
**NOTE**: many of the tools are pre-installed and configured for direct use on Azure Data Science Virtual Machine.

### Scalable analytics
* [dplyrXdf](https://github.com/RevolutionAnalytics/dplyrXdf) - a dplyr backend for Revolution Analytics xdf files.
* [sparklyr](http://spark.rstudio.com/) - R interface for Apache Spark.
* [SparkR](https://spark.apache.org/docs/latest/sparkr.html) - SparkR is an R package that provides a light-weight frontend to use Apache Spark from R.

### Deep learning
* [CNTK-R](https://github.com/Microsoft/CNTK-R) - R bindings to the CNTK library.
* [tensorflow](https://tensorflow.rstudio.com/) - R interface to Tensorflow.
* [mxnet](https://mxnet.incubator.apache.org/api/r/index.html) - The MXNet R package brings flexible and efficient GPU computing and state-of-art deep learning to R.
* [keras](https://keras.rstudio.com/) - R interface to Keras.
* [darch](https://github.com/maddin79/darch) - Create deep architectures in R. 
* [deepnet](https://cran.r-project.org/web/packages/deepnet/index.html) - Implement some deep learning architectures and neural network algorithms, including BP,RBM,DBN,Deep autoencoder and so on.
* [gpuR](https://github.com/cdeterman/gpuR) - R interface to use GPU.

### Compositive
* [RevoScaleR](https://docs.microsoft.com/en-us/machine-learning-server/r-reference/revoscaler/revoscaler) - a collection of portable, scalable, and distributable R functions for importing, transforming, and analyzing data at scale. 
* [MicrosoftML](https://docs.microsoft.com/en-us/machine-learning-server/r-reference/microsoftml/microsoftml-package) - a package that provides state-of-the-art fast, scalable machine learning algorithms and transforms for R.
* [h2o](https://github.com/h2oai/h2o-3) - R interface to H2O.

## Interaction and remote access
The R packages and tools in this category help data scientists or developers to easily remote access or interact with Azure cloud instances or services for convenient development.

* [mrsdeploy](https://docs.microsoft.com/en-us/machine-learning-server/r-reference/mrsdeploy/mrsdeploy-package) - an R package that provides functions for establishing a remote session in a console application and for publishing and managing a web service that is backed by the R code block or script you provided.
* [R Tools for Visual Studio](https://www.visualstudio.com/vs/rtvs/) - IDE with R support.
* [RStudio Server](https://www.rstudio.com/products/rstudio/#Server) - IDE for remote R session with access via Internet browser.
* [JupterHub](https://jupyterhub.readthedocs.io/en/latest/) - Jupyter notebook with multi-user access.
* [IRKernel](https://github.com/IRkernel/IRkernel) - R kernel for Jupyter notebook. 

## Application and service deployment 
The R packages and tools in this category are used for deploying an R-based analytics or applicaiton as services or interfaces that can be conveniently consumed by end-users or developers. 

* [mrsdeploy](https://docs.microsoft.com/en-us/machine-learning-server/r-reference/mrsdeploy/mrsdeploy-package) - an R package that provides functions for deploying easily-consumable service within R session. 
* [AzureML](https://cran.r-project.org/web/packages/AzureML/index.html) - an R package to allow one to interact with [Azure Machine Learning Studio](https://studio.azureml.net/) for publishing R functions as API services. 
* [Azure Container Instances](https://azure.microsoft.com/en-us/services/container-instances/) - Azure service to allow running a containerized R analytics on cloud.
* [Azure Container Services](https://azure.microsoft.com/en-us/services/container-service/) - Azure service that simplifies deployment, management, and operation of orchestrated containers of R analytics. 
* [Shiny server](https://www.rstudio.com/products/shiny/shiny-server/) - Develop and publish Shiny based web applications online.