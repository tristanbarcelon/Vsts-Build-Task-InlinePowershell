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

[See my blog](https://pgroene.wordpress.com/)

[Sources](https://github.com/XpiritBV/Vsts-Build-Task-InlinePowershell)

## Tips and Tricks

[Use VSTS variables](https://pgroene.wordpress.com/2017/12/07/use-vsts-variables-inline-powershell)

[Let your task fail](https://pgroene.wordpress.com/2017/12/08/let-your-inline-powershell-task-fail)

[Set progress](https://pgroene.wordpress.com/2017/12/11/4256)

[Change buildnumber](https://pgroene.wordpress.com/2017/12/12/set-buildnumber-from-inline-powershell)

[VSTS Powershell command overview](https://pgroene.wordpress.com/2017/12/13/vsts-powershell-commands) 

[Call a WebHook](https://pgroene.wordpress.com/2017/12/14/call-a-webhook-from-inline-powershell)

[Download a file](https://pgroene.wordpress.com/2017/12/15/download-a-file-from-inline-powershell)

[Install a Powershell Module](https://pgroene.wordpress.com/2017/12/18/install-a-powershell-module-inline-powershell-vsts)

[Navigate VSTS as filesystem](https://pgroene.wordpress.com/2017/12/19/navigate-vsts-project-as-filesystem-from-inline-powershell)

[Make VSTS API Rest calls](https://pgroene.wordpress.com/2017/12/20/vsts-rest-api-from-inline-powershell)

[Script example: Act on failed build ](https://pgroene.wordpress.com/2017/12/21/let-your-build-work-for-you-shorten-the-feedback-loop)

