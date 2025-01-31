# Developing Scripts Using Development Endpoints<a name="dev-endpoint"></a>

AWS Glue can create an environment—known as a *development endpoint*—that you can use to iteratively develop and test your extract, transform, and load \(ETL\) scripts\. You can create, edit, and delete development endpoints using the AWS Glue console or API\.

**Note**  
Development endpoints are not supported for use with AWS Glue version 2\.0 jobs\. For more information, see [Running Spark ETL Jobs with Reduced Startup Times](https://docs.aws.amazon.com/glue/latest/dg/reduced-start-times-spark-etl-jobs.html)\.

## Managing your Development Environment<a name="dev-endpoint-managing-dev-environment"></a>

When you create a development endpoint, you provide configuration values to provision the development environment\. These values tell AWS Glue how to set up the network so that you can access the endpoint securely and the endpoint can access your data stores\.

You can then create a notebook that connects to the endpoint, and use your notebook to author and test your ETL script\. When you're satisfied with the results of your development process, you can create an ETL job that runs your script\. With this process, you can add functions and debug your scripts in an interactive manner\.

Follow the tutorials in this section to learn how to use your development endpoint with notebooks\.

**Topics**
+ [Managing your Development Environment](#dev-endpoint-managing-dev-environment)
+ [Development Endpoint Workflow](dev-endpoint-workflow.md)
+ [How AWS Glue Development Endpoints Work with SageMaker Notebooks](dev-endpoint-how-it-works.md)
+ [Adding a Development Endpoint](add-dev-endpoint.md)
+ [Viewing Development Endpoint Properties](console-development-endpoint.md)
+ [Accessing Your Development Endpoint](dev-endpoint-elastic-ip.md)
+ [Creating a Notebook Server Hosted on Amazon EC2](console-ec2-notebook-create.md)
+ [Tutorial Setup: Prerequisites for the Development Endpoint Tutorials](dev-endpoint-tutorial-prerequisites.md)
+ [Tutorial: Set Up a Local Apache Zeppelin Notebook to Test and Debug ETL Scripts](dev-endpoint-tutorial-local-notebook.md)
+ [Tutorial: Set Up an Apache Zeppelin Notebook Server on Amazon EC2](dev-endpoint-tutorial-EC2-notebook.md)
+ [Tutorial: Set Up a Jupyter Notebook in JupyterLab to Test and Debug ETL Scripts](dev-endpoint-tutorial-local-jupyter.md)
+ [Tutorial: Use a SageMaker Notebook with Your Development Endpoint](dev-endpoint-tutorial-sage.md)
+ [Tutorial: Use a REPL Shell with Your Development Endpoint](dev-endpoint-tutorial-repl.md)
+ [Tutorial: Set Up PyCharm Professional with a Development Endpoint](dev-endpoint-tutorial-pycharm.md)
+ [Advanced Configuration: Sharing Development Endpoints among Multiple Users](dev-endpoint-sharing.md)