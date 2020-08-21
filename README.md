# Google-Cloud-Commands (Cloud Shell)
![image](https://github.com/sanket9006/Google-Cloud-Commands/blob/master/Others/google-cloud.png)
> Cloud Shell comes preinstalled with specific command line tools. The main GCP toolkit is gcloud, which is used for many tasks on the platform, like resource management and user authentication
 

## <p> Setting up prebuild E-Commerce website using Google Cloud and GitHub </p>

    cd ~
    git clone https://github.com/googlecodelabs/monolith-to-microservices.git
    cd ~/monolith-to-microservices
    ./setup.sh
    
## <p> Create Cluster</p>
    gcloud container clusters create io
    gcloud container clusters create fancy-cluster --num-nodes 3
        
    Created GKE cluster named fancy-cluster with 3 nodes

## <p> List out all present instances </p>
        > gcloud compute instances list
        

## <p>In Cloud Shell, set the default zone:</p>

>gcloud config set compute/zone us-central1-a

## <p>Set the default region:</p>

>gcloud config set compute/region us-central1

## <p> Download any file using wget
> sudo wget https://launcher.mojang.com/v1/objects/d0d0fe2b1dc6ab4c65554cb734270872b72dadd6/server.jar





## <p> Create Bucket </p>
> gsutil mb gs://<BUCKET_NAME>

> gsutil mb gs://2b1dc6ab4c65554cb73









## <p> Copy files to Bucket  </p>
> gsutil cp [MY_FILE] gs://[BUCKET_NAME]

> gsutil cp setup.html gs://2b1dc6ab4c65554cb73





## <p> list the available VPC networks</p>
> gcloud compute networks list




## <p> Make Copy</p>
> cp setup.html setup2.html

> cp setup.html setup3.html



## <p> To list the available VPC subnets</p>
> gcloud compute networks subnets list --sort-by=NETWORK


## <p> Set time zone subnets</p>
> gcloud config set compute/zone us-central1-b


## <p> Create Virtual Machine Instance</p>
> gcloud compute instances create gcelab2 --machine-type n1-standard-2 --zone us-central1-c


## <p> List the files in our current directory</p>
> ls




## <p> To edit a file</p>
> nano filename.txt

## <p> output the contents of a file</p>
> cat filename.txt

## <p> update your OS</p>
> apt-get update

## <p> Install NGINX</p>
> apt-get install nginx -y

## <p> Check that NGINX is running</p>
> ps auwx | grep nginx

## <p> To disconnect from SSH</p>
> exit

