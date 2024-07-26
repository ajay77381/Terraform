# Store remote state

Reference Video URL - https://developer.hashicorp.com/terraform/tutorials/certification-associate-tutorials-003/aws-remote

you have built, changed, and destroyed infrastructure from your local machine. This is great for testing and development, but in production environments you should keep your state secure and encrypted, where your teammates can access it to collaborate on infrastructure.  The best way to do this is by running Terraform in a remote environment with shared access to state.
Terraform allows teams to easily version, audit, and collaborate on infrastructure changes. It also securely stores variables, including API tokens and access keys, and provides a safe, stable environment for long-running Terraform processes
create a directory named learn-terraform-aws-instance and paste this code into a file named main.tf.If you have alrady not created.

![image](https://github.com/user-attachments/assets/ce2cbbfb-15aa-4c0a-9102-f8195d5ba243)

Run terraform init to initialize your configuration directory and download the required providers. It is safe to re-run this command even if you have already done so in this directory.

![image](https://github.com/user-attachments/assets/ac61838c-c963-43a1-a9eb-0092563220da)

Next, apply your configuration. Type yes to confirm the proposed changes.

![image](https://github.com/user-attachments/assets/3cb566f2-07cd-4370-afa8-65cb901d6106)

Terraform provisioned an AWS EC2 instance and stored data about the resource in a local state file.

#Set up HCP Terraform

![image](https://github.com/user-attachments/assets/e0ce7fdc-9242-4efb-9d8f-2c1c71fa20b1)

#Login to HCP Terraform

Next, log into your HCP Terraform account with the Terraform CLI in your terminal.

![image](https://github.com/user-attachments/assets/51c6228e-8ce7-428f-89a7-cc3a3f1db1d1)

Confirm with a yes and follow the workflow in the browser window that will automatically open. You will need to paste the generated API key into your Terminal when prompted. For more detail on logging in, follow the Authenticate the CLI with HCP Terraform tutorial.

# Initialize Terraform



