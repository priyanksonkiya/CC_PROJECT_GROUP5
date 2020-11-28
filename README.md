# CC_PROJECT_GROUP5
# ARM-Templates
To implement infrastructure as code for your Azure solutions, use Azure Resource Manager (ARM) templates. The template is a JavaScript Object Notation (JSON) file that defines the infrastructure and configuration for your project. The template uses declarative syntax, which lets you state what you intend to deploy without having to write the sequence of programming commands to create it. In the template, you specify the resources to deploy and the properties for those resources.

## It is:

- Template-driven 
- Declarative 
- Idempotent 
- Multi-service 
- Multi region
- Extensible 

## Template deployment types:

  The **complete** mode deletes any objects that do not appear in the template and the resource group you are deploying to. In this scenario, what you get is the ability to know that whenever you deploy you will be in exactly the same state.

The **incremental** deployment uses the template to add additional resources to an existing resource group. The benefit of this is that you don’t lose any infrastructure that is missing from the template but the downside is that you will have to clear up any old resources some other way.

## What don’t they do
The ARM API deploys resources to Azure, but doesn’t deploy code onto those resources. For example you can use ARM to deploy a virtual machine with SQL Server already installed but you can’t use ARM to deploy a database from an SSDT DacPac.
To save time when designing solutions, it is important to understand that ARM API is used simply for resources and we need to use some other technology such as DSC or PowerShell to manage the deployments onto the infrastructure once it is deployed.

## TEMPLATE FILE:
Within your template, you can write template expressions that extend the capabilities of JSON. These expressions make use of the functions provided by Resource Manager.
### The template has the following sections:
- **Parameters** - Provide values during deployment that allow the same template to be used with different environments.
- **Variables** - Define values that are reused in your templates. They can be constructed from parameter values.
- **User-defined functions** - Create customized functions that simplify your template.
- **Resources** - Specify the resources to deploy.
- **Outputs** - Return values from the deployed resources.


THIS CONTAINS ALL THE FILES FOR CLOUD COMPUTING PROJECT AND ASSIGNMENTS FOR GROUP 5 . <br />
ALL THE THREE FILES - chooseVM.txt , cpuALERT.txt , VnetWithSubnets.txt are the JSON files of the ARM templates. 
ThE video of our presentation group5_CC_presentation.mp4 is available at - <br />
https://drive.google.com/file/d/10mjqGMgJD-XuM3YQaxJiQ9d3K4VzScTO/view?usp=sharing <br />
<br />
The presentation is named as - CloudComputingProject_ArmTemplates.pdf and is  also available here at -<br />
https://drive.google.com/file/d/15-ga1svTDzWNwTtZ5zq_ai2jxFscTcwS/view?usp=sharing<br />
<br />
The report/paper is named as - ARM templates revise.pdf and is also  available at - <br />
https://drive.google.com/file/d/1H6AMTbi6ggJq4tjkgjGHIaqLmfZ3cmS1/view?usp=sharing <br />
<br />


Just in case if required all the files are also available at - <br />
 this location - https://drive.google.com/drive/folders/1HBAL_kyZLYGplvvuR2f8a6oYyFZfSw_S?usp=sharing <br />
Thank You so much - <br />




PRIYANK SONKIYA 17DCS009.<br />
RACHIT JAIN 17UCS118.<br />
NISHA GOYAL 17UCS112.<br />
SHREYA KHANDELWAL 17UCS154.<br />
