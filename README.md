starcluster-tools
=================

To get starcluster running: 

1. Pull the development version from git and install it using pip

          pip install git+git://github.com/jtriley/StarCluster.git

2. Run 

          starcluster help

3. Select "[2] Write config template to /home/user/.starcluster/config"

4. Replace your .starcluster/config file with the config file from this git repo

5. Enter your AWS_ACCESS_KEY_ID, AWS_SECRET_ACCESS_KEY, and CLUSTER_USER

6. See [Starcluster's quick start guide](http://star.mit.edu/cluster/docs/0.92rc2/quickstart.html) for help creating a SSH key, editing the config file to use your newly created key, and launching your first cluster
