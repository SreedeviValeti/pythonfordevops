**Steps to Automate Compliance Reporting When Termination Protection Isn't On** 

As we all know with “Termination Protection” feature in EC2, we can protect our EC2 servers from accidental deletion.

Imagine for one our production server “Termination Protection” feature is not enabled and it deleted accidentally, what would be your immediate action?  obviously we check for AMI backup of the server right? what if due to some misassumptions or misconfigurations backups also not triggered for that server? It would become our last day right? to overcome this scenarios we are automating the task which checks all running servers whether  “Termination Protection” feature is enabled or not?  if any of the server Termination Protection Isn't On, it will send email alert with EC2 Instance Id’s saying that to enable “Termination Protection”. What if Termination Protection” is enabled on all servers? this script will automatically exit the runtime 

What a cool automation right? let’s start …….

you can find detailed blog here [Blog](https://sreedeviblog.hashnode.dev/steps-to-automate-compliance-reporting-when-termination-protection-isnt-on)
