# Second-scheduler-in-cluster
Creating second scheduler in kubernetes cluster
## Step 1
     Account for the scheduler service is created.
## Step 2
     Binding new account to the cluster role system:kube-scheduler.
## Step 3
     Binding new account to the cluster role system:volume-scheduler.
## Step 4
     Creating config file for the second application kube-scheduler.
## Step 5
     Change the master node name in the section spec.nodeSelector: to your node name.
