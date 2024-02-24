# Cloud-Native-Monitoring-App
1.Python and How to create Monitoring Application in Python using Flask and psutil.  
2.How to run a Python App locally.  
3.Learn Docker and How to containerize a Python application  
&nbsp;&nbsp;&nbsp;&nbsp; i.Creating Dockerfile  
&nbsp;&nbsp;&nbsp;&nbsp; ii.Building DockerImage  
&nbsp;&nbsp;&nbsp;&nbsp; iii.Running Docker Container  
&nbsp;&nbsp;&nbsp;&nbsp; iv.Docker Commands  
4.Create ECR repository using Python Boto3 and pushing Docker Image to ECR  
5.Learn Kubernetes and Create EKS cluster and Nodegroups  
6.Create Kubernetes Deployments and Services using Python!  
## ✨Let’s Start the Project ✨  

## Part 1: Deploying the Flask application locally
### Step 1: Clone the code
'''python
Clone the code from the repository: 
'

git clone <repository_url>
Step 2: Install dependencies
The application uses the psutil and Flask, Plotly, boto3 libraries. Install them using pip:

pip3 install -r requirements.txt
Step 3: Run the application
To run the application, navigate to the root directory of the project and execute the following command:

python3 app.py
This will start the Flask server on localhost:5000. Navigate to http://localhost:5000/ on your browser to access the application.
