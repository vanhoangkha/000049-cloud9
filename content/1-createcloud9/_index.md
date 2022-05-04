+++
title = "Create Cloud9 instance"
weight = 1
chapter = false
pre = "<b>1. </b>"
+++

#### Create Cloud9 instance.

In this step, we will access the Cloud9 service administration interface and proceed to create a Cloud9 instance.

1. Sign in to the AWS Management Console.

![Cloud9](/images/cloud9/001.png?width=90pc)

2. Click on the search box, type **Cloud9**.
  + Click on **Cloud9** icon to go to Cloud9 admin interface.

![Cloud9](/images/cloud9/002.png?width=90pc)

3. At the Cloud9 admin interface.
  + Click **Create environment**.

![Cloud9](/images/cloud9/003.png?width=90pc)

4. At **Name environment** page.
  + Name your Cloud9 instance.
  + Example: **cloud9instance**.
  + Click **Next step**.


![Cloud9](/images/cloud9/004.png?width=90pc)

5. At **Configure settings** page.
  + Section **Environment settings**.
    + Environment type : Select **Create a new EC2 instance for environment (direct access)**.
    + Instance type : Select **t2.micro**.
    + Platform : Select **Amazon Linux2**.

    
![Cloud9](/images/cloud9/005.png?width=90pc)

6. Drag down the screen.
  + Cost-saving setting : select **After 30 minutes**. Allows to automatically stop Cloud9 instances to save costs.
  + Click **Next step**.


![Cloud9](/images/cloud9/006.png?width=90pc)

7. At **Review** page.
  + Check the selected configuration.
  + Scroll to the bottom of the page, click **Create environment**.

8. It will take a few minutes for Cloud9 Instance to be initialized.

![Cloud9](/images/cloud9/007.png?width=90pc)

9. Click the close icon to close the **Welcome** and **AWS Toolkit** tabs if not needed.

![Cloud9](/images/cloud9/008.png?width=90pc)

Congratulations on completing the creation of Cloud9 instance, in the next steps we will try to perform some basic operations on Cloud9.