Using vagrant with aws

these files were create to allow user to use Vagrant with AWS ,where the VMs managed by Vagrant are actually instances running on AWS.

INSTRUCTIONS
1. Vagrant requires that a "dummy box" be installed for use with AWS. Run this command to install the dummy box:
  vagrant box add <box-name> https://github.com/mitchellh/vagrant-aws/raw/master/dummy.box

2. Install the Vagrant AWS provider by running vagrant plugin install vagrant-aws
3. In a terminal window, set the AWS_ACCESS_KEY_ID and AWS_SECRET_ACCESS_KEY environment variables to your AWS access key ID and AWS secret access key, respectively.

		export AWS_ACCESS_KEY_ID="ACCESS_KEY"
		export AWS_SECRET_ACCESS_KEY="PASTE_SECRET_KEY"
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
"README.md" 11L, 632C

Using vagrant with aws
Last login: Sat Aug 19 20:39:49 on ttys000


Using vagrant with aws

these files were create to allow user to use Vagrant with AWS ,where the VMs managed by Vagrant are actually instances running on AWS.

INSTRUCTIONS
1. Vagrant requires that a "dummy box" be installed for use with AWS. Run this command to install the dummy box:

  vagrant box add <box-name> https://github.com/mitchellh/vagrant-aws/raw/master/dummy.box
2. Install the Vagrant AWS provider by running vagrant plugin install vagrant-aws
3.In a terminal window, set the AWS_ACCESS_KEY_ID and AWS_SECRET_ACCESS_KEY environment variables to your AWS access key ID and AWS secret access key, respectively.
	export AWS_ACCESS_KEY_ID="PASTE_ACCESS_KEY"
	export AWS_SECRET_ACCESS_KEY="PASTE_KEY_HERE"
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
~
"README.md" 11L, 632C      
