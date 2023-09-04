# -ISEC6000-assignment1

This README provides step-by-step instructions for setting up initial infrastructure. 

# Step 1: Create a Kubernetes Cluster on GKE

1. Log in to Google Cloud Console.
2. Go to the Kubernetes Engine section in the left sidebar and click "Create Cluster."
3. Configure your cluster settings:
   - Provide a unique cluster name.
   - Select a location for your cluster.
   - Configure the node pool if needed.
4. Select the Kubernetes version.
5. Click "Create" to provision your GKE cluster.

# Step 2: Install and configure kubectl

1. After creating the GKE cluster, configure the local environment to use kubectl to interact with the cluster.
2. In the Google Cloud Console, go to the "Kubernetes Engine" and move to the "Clusters" section.
3. Find your cluster and click the "Connect" button next to it.
4. Authenticate kubectl with the GKE cluster using the instructions provided.

# Step 3: Set Up a Private GitHub Repository

1. Log in/Create a GitHub account.
2. Click on the '+' icon at the top right corner of the GitHub dashboard and select "New repository."
3. Choose a repository name for the project.
4. Select "Public" for the repository visibility.
5. Add a description (optional) and choose whether to initialize the repository with a README.
6. Click "Create repository."
7. Push the initial setup code to the repository. 


