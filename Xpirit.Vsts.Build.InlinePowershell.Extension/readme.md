# InlinePowershell

The Inline PowerShell VSTS task enables you to execute PowerShell from a textbox within your build or release pipeline. You can run a PowerShell script on you agent or as Azure Powershell.

# Documentation

## Configure the task

Add the task to you build or release pipeline. Select the +Add tasks -> Utility -> Run Inline PowerShell:

![alt tag](https://pgroene.files.wordpress.com/2016/05/addtask.png?w=840)

Next you can enter the PowerShell script into the textbox:

![alt tag](https://pgroene.files.wordpress.com/2016/05/enterpowershell.png?w=840)

Run your build or release to see the ‘Hello world’ in the logs.

## Adding arguments

Next you will be able to add argument to pass custom build variables. You need to pass them as arguments if they are marked as secret.

![alt tag](https://pgroene.files.wordpress.com/2016/05/enterpowershellarguments.png?w=840)

This will give you the following output:

![alt tag](https://pgroene.files.wordpress.com/2016/05/enterpowershelloutput.png?w=840)

Variables marked a secret will be shown as ********. This to prevent them to be reviled to everybody with access to the logs.

[See my blog for more tasks](https://pgroene.wordpress.com/)
[Sources](https://github.com/XpiritBV/Vsts-Build-Task-InlinePowershell)


