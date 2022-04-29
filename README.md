# k8s-grpc

### Overview 
You must take your application and move it to a Kubernetes environment (e.g. using k8s) while making it more flexible to analyse multiple data sources. You must also implement testing and monitoring for the application. You must also create a serverless function that could potentially be useful for your application. 

### Part 1 – Move to Kubernetes
Get your application running using Kubernetes.

### Part 2 – Testing and Monitoring
You are to address the testing and monitoring of your application. You are to develop 1 test and 1 monitoring solution for your application. 

### Part 3 – A serverless function
Using Kubeless, create a function that would be useful for your application. It does not have to be called from within your application – it should run as per the quickstart guide from the command line. However, you must explain where in your application it would be placed and how it would be useful. Explain the inputs and outputs to/from your function. 

See the following quick start guide: https://kubeless.io/docs/quick-start/ 
The hello-world function there is not much use. Come up with a useful function for your application. The function does not have to be embedded into your application – i.e. just run it from the command line as per the quick start guide. Include a screenshot of the function being run with its return value(s). 

### What to submit: 
* The Word form containing all requested explanations (e.g. why that test, why that monitor, the purpose of your serverless function, anything else you think is relevant to explain your efforts) and screenshots showing whatever you got up and running.
* A zip file containing your code and config files.
