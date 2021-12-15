# Cloud Deploy Quickstart

reference:  
https://cloud.google.com/deploy/docs/quickstart-basic

##
In this quickstart we will show 

 you how to use Google Cloud Deploy to deliver a sample application image named echoserver to a sequence of two Google Kubernetes Engine clusters.

In this quickstart, you'll do the following:

Create the two clusters.

Create a Skaffold configuration and a Kubernetes manifest to specify the (pre-built) container image to deploy.

Define your Google Cloud Deploy delivery pipeline and deployment targets, which point to the two clusters.

You can define your targets in the same file as the delivery pipeline or in a different file or files. For simplicity in this quickstart, you'll put them in the same file.

Instantiate your delivery pipeline by creating a release, which automatically deploys to the first target.

Promote the release to the second target.

View both rollouts in Cloud Console.
:q

