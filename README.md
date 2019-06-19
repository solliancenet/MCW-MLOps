# MLOps
Trey Research Inc. delivers innovative solutions for manufacturers. They specialize in identifying and solving problems for manufacturers that can run the range from automating away mundane but time-intensive processes to delivering cutting edge approaches that provide new opportunities for their manufacturing clients. Trey Research has decades specializing in data science and application development that until now were separate units. They have seen the value created by the ad-hoc synergies between data science and app development, but they would like to unlock the greater, long term value as they formalize their approach by combining the two units into one, and follow one standardized process for operationalizing their innovations.

As their first effort of this combined initiative, they would to define a process for operationalizing deep learning that encompasses all phases of the application life cycle along with model creation and deployment of a deep learning model. For this first proof of concept, they would like to focus on component compliance. Specifically they are looking to leverage Deep Learning technologies with Natural Language Processing techniques to scan through vehicle specification documents to find compliance issues with new regulations. Even though this first scenario is focused on vehicle components, they believe this approach will generalize to any scenario involving an inventory of components (which all of their manufacturing customers deal with). The component descriptions (which are free form text) are entered and managed via a web application. This web application take new component descriptions entered by authorized technicians and labels the component as compliant or non-compliant based on the text. 

They want to ensure the overall process they create enables them to update both the underlying model and the web app in one, unified pipeline. They also want to be able to monitor the model's performance after it is deployed so they can be proactive with performance issues.


## Target audience
-   Data Scientists
-   App Developers
-   AI Engineers
-   DevOps Engineers 


## Abstract

### Workshop
In this workshop, you will learn how Trey Research can leverage Deep Learning technologies to scan through their vehicle specification documents to find compliance issues with new regulations, and manage the classification thru their web application. The entire process from model creation, application packaging, model deployment and application deployment needs to occur as one unified repeatable, pipeline. 

At the end of this workshop, you will be better able to design and implement end-to-end solutions that fully operationalize deep learning models, inclusive of all application components that depend on the model.

### Whiteboard design session *(this will go in the readme and in the WDS document)*
In this whiteboard design session, you will work in a group to design the process Trey Research can follow for orchestrating and deploying updates to the application and the deep learning model in a unified way. You will learn how Trey Research can leverage Deep Learning technologies to scan through their vehicle specification documents to find compliance issues with new regulations. You will standardize the model format to ONNX and observe how this simplifies inference runtime code, enabling pluggability of different models and targeting a broad range of runtime environments and most importantly improves inferencing speed over the native model. You will design a DevOps pipeline the coordinate retrieving the latest best model from the model registry, packaging the web application, deploying the web application and inferencing web service. You will also learn how to monitor the model's performance after it is deployed so Trey Research can be proactive with performance issues.

At the end of this whiteboard design session, you will be better able to design end-to-end solutions that fully operationalize deep learning models, inclusive of all application components that depend on the model.


### Hands-on lab *(this will go in the readme and in the HOL document)*
In this hands-on lab, you will learn how Trey Research can leverage Deep Learning technologies to scan through their vehicle specification documents to find compliance issues with new regulations. You will standardize the model format to ONNX and observe how this simplifies inference runtime code, enabling pluggability of different models and targeting a broad range of runtime environments and most importantly improves inferencing speed over the native model. You will build a DevOps pipeline the coordinate retrieving the latest best model from the model registry, packaging the web application, deploying the web application and inferencing web service. After a first successful deployment, you will make updates to both the model and the and web application and execute the pipeline once for to achieve an updated deployment. You will also learn how to monitor the model's performance after it is deployed so Trey Research can be proactive with performance issues.

At the end of this hands-on lab, you will be better able to you will be better able to implement end-to-end solutions that fully operationalize deep learning models, inclusive of all application components that depend on the model.


## Azure services and related products
-	Azure Container Instances
-	Azure DevOps
-   Azure Kubernetes Service
-   Azure Machine Learning Service
-	Azure Notebooks
-	ML Ops
-   ONNX
-   
## Related references
*This should be a list of and links to prereqs, architectural diagrams, supporting docs, or briefing decks related to the material.* 
- [MCW](https://github.com/Microsoft/MCW)
