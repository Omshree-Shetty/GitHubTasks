# <p align ="center"> **KT PLAN** :writing_hand:  </p>

_<p align= "center"> plan for ***App onboarding Team***</p>_

---

# **DAY 1**

---

### GitHub & Github Commands :smiley: :nerd_face

---

>First Create a GitHub Account:

- [How to create GitHub Account](https://docs.github.com/en/get-started/onboarding/getting-started-with-your-github-account)

>Download Git

- [Download Git for Windowa, Mac & Linux/Unix](https://git-scm.com/downloads)

>Install and use Git on Windows

- [Step-By-Step Tutorial for Windows](https://phoenixnap.com/kb/how-to-install-git-windows)

- [Step-By-Step Tutorial for Mac](https://phoenixnap.com/kb/install-git-on-mac)

- [Step-By-Step Tutorial for Linux](https://www.makeuseof.com/install-configure-git-on-linux/)  

---

<h2><span style="color:lightblue">What is Github? :thinking:</span> </h2>

To put it simply, GitHub is a file or code-sharing service that allows users to collaborate with others.  
GitHub is a popular piece of software that is commonly used for version control. It comes in handy when more than one person is working on a project.
Version control lets you keep track of your work and easily explore the changes you've made, whether it's data, coding scripts, notes, or anything else.

![Github working](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2017/11/GitHub-How-to-use-GitHub-Edureka-373x300.png)

---

<h2><span style="color:lightblue">What is Git :thinking: </span> </h2>

Git allows users to use simple commands to track code changes and manage their projects.  
Git is a distributed version control system for tracking changes in source code during software development. It is intended to help programmers coordinate their actions, but it can also be used to track changes in any set of files.

---

<h2><span style="color:lightblue"> Github Vs Git :thinking: </span> </h2>

GitHub | Git
 ------------ | -------------
GitHub is a service. | Git is a software.
GitHub is a graphical user interface | Git is a command-line tool
GitHub is hosted on the web|  Git is installed locally on the system
GitHub is focused on centralized source code hosting.|  Git is focused on version control and code sharing.
GitHub is a hosting service for Git repositories.|  Git is a version control system to manage source code history.
GitHub includes a free-tier and pay-for-use tier.|  Git is open-source licensed.

---

# Let's Start with the Commands :memo::pencil

Note: The commands give below can be used on CMD/Command Line Console/Terminal. _You can use any editor, I am using Visual Studio Code [Link and steps on how to install VS](https://www.geeksforgeeks.org/how-to-install-git-in-vs-code/)_ In Visual Studio, Clicking 'CTRL+J' will open the terminal


SETUP and INIT
---

| Command |  Use Case |  Example |
| ------- | ----------- | ----------- |
`git config --global user.name "[username]"` | It will set the your username of github in terminal | ![eg](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/1-9.png)
`git config --global user.email "[github email]"` | It will set the your email | ![eg](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/1-9.png)
`git init` | initializes a Git repository | ![eg](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/2-6.png) <BR> you can find the url ![here](/Images/clone_url.png) or click on dropdown from code url ![this](/Images/code_url.PNG)
`git clone url`  |create local copy of remote repository(URL) | ![eg1](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/4-4.png)   ![eg2](https://intellipaat.com/mediaFiles/2019/07/GItCommand12.png)
---

STAGE AND SNAPSHOT
---

---
| Command |  Use Case |  Example |
| ------- | ----------- | ----------- |
`git status`    |  show status of git  | ![eg](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/15-1.png)
`git add [file]`    | add a file as it looks now to your next commit (staging area) | ![eg](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/5-4.png)
`git add .` | adds all the files to staging area | This is how add .  works <br>![add](/Images/add.PNG)
`git reset [file]` |unstage a file while retaining the changes in working directory | ![eg](https://static.javatpoint.com/tutorial/git/images/git-reset3.png)
`git diff` |diff of what is changed  between the states | ![eg](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/9-2.png)
`git commit -m “[descriptive message]”` | commit your staged content as a new commit snapshot |   ![eg](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/7-3.png)
`git commit -am "[description message]"` | adds and commits together(only applicable to the files that are already pushed on remote repo) | ![am](/Images/am.PNG)
---

BRANCH
---

---
| Command |  Use Case |  Example |
| ------- | ----------- | ----------- |
`git branch` |list your branches. a * will appear next to the currently active branch | ![eg](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/23.png)
`git branch -d [branch name]` | deletes the branch  | ![eg1](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/25.png) ![eg2](https://intellipaat.com/mediaFiles/2019/07/GItCommand14.png)
`git branch [branch name]` | creates a new branch | ![eg](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/24.png)
`git checkout -b [branch name]` |create a new branch and switch to it | ![eg](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/28.png)
`git checkout` |switch to another branch | ![eg](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/27.png)
`git branch -m [old branch name] [new branch name]` | rename a local branch | ![img](/Images/rename.PNG)
`git merge [branch name]` | merge the specified branch into active branch  | ![eg](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/31-1.png)
`git merge [source branch] [target branch]` | merge a branch into a target branch | ![eg](https://intellipaat.com/mediaFiles/2019/07/GItCommand25.png)
`git log`| show all commits in the current branch’s history | ![eg](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/18-768x293.png)
---

UPDATE
---

---
| Command |  Use Case |  Example |
| ------- | ----------- | ----------- |
`git remote add [alias] [url]` |add a git URL as an alias | ![eg](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/32.png)  
`git fetch [alias]` | fetch down all the branches from that Git remote  | ![eg](https://intellipaat.com/mediaFiles/2019/07/GItCommand27.png)
  `git push [alias(origin)] [branch name]` | push branch to the remote repository | ![eg](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/33.png)
`git push -u origin [branch name]` | push changes to remote repo and remembers the branch _-u: upstream_ | ![img](/Images/pushu.PNG)
`git pull` | fetch and merge any commits from the remote repository to local repository |![eg](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/38.png)
`git rm [file name]` | This command will delete the file | ![eg](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/16-2.png)

---
---
# **DAY 2**

<h2><span style="color:lightblue"> What is PR(Pull Request)? :thinking: </span> </h2>
Pull requests let you tell others about changes you've pushed to a branch in a repository on GitHub. Once a pull request is opened, you can discuss and review the potential changes with collaborators and add follow-up commits before your changes are merged into the base branch.

---
<h2><span style="color:lightblue"> What is forking? :fork_and_knife: </span></h2>
A fork is a copy of a repository. This is useful when you want to contribute to someone else's project or start your own project based on theirs.  
Forking a repository allows you to freely experiment with changes without affecting the original project.
It is a concept of making copy of the main repository to your account so that you can make modifications in it. You can Submit pull request to the main repository with the modifications. It will make sure that the main repository is prevented from unwanted changes.
Here is the icon of fork in github:


![fork_button](http://www.testingdocs.com/questions/wp-content/uploads/Fork-a-GitHub-Repository.png)

Here is the second page after you click on fork button 
<br>
![fork_page](/Images/fork.PNG)
___

<h2><span style="color:lightblue">What is merge conflict and how to resolve it? :thinking: </span></h2>

Merge conflicts happen when you merge branches that have competing commits, and Git needs your help to decide which changes to incorporate in the final merge.  
To resolve a merge conflict, you must manually edit the conflicted file to select the changes that you want to keep in the final merge.
There are a couple of different ways to resolve a merge conflict:

    -If your merge conflict is caused by competing line changes, such as when people make different changes to the same line of the same file on different branches in your Git repository, you can resolve it on GitHub using the conflict editor.   

    -For all other types of merge conflicts, you must resolve the merge conflict in a local clone of the repository and push the change to your branch on GitHub. You can use the command line or a tool like GitHub Desktop to push the change. 
___

<h2><span style="color:lightblue"> What is read md file? Why is it used? :thinking: </span></h2>

A README file is an essential guide that gives other developers a detailed description of your GitHub project.
It is a text file describing what the project is about, what it does, how to use the project, and other information regarding the same.
The readme file is used to explain what is uploaded and how we can install or use it. It even allows the uploader to add images and videos to help the reader navigate through the project. A well-written readme file is more important if you intend to show these projects in your resume.

---

# Let's Start with the Basix Syntax of MarkDown :memo::pencil

Basic Syntax
----

___

| Element | Markdown Syntax |
| ------- | ----------- |
Heading | # followed by the text (upto 6#s)<br>eg: <br> # H1 <br> ## H2 <br> ### H3
Italic | Wrap the text with 1 asterisks/underscores  <br>eg:_italicized text_
Bold | Wrap the text with 2 asterisks/underscores<br> eg: **bold text**
Simultaneously Bold & Italic | Wrap the text with 3 asterisks/underscore <br>eg: ***Bold & Italic***
Strike Through | Wrap the text in two tildes <br>eg: ~~Strikethrough~~
Blockquote | Precede the first line of block quote with angle bracket <br>eg: >blockquote
Ordered List | 1. First item <br> 2. Second item <br> 3. Third item
Unordered List    | - First item <br> - Second item <br> - Third item  
Code | To reference snippets of code we start and end the code with backticks <br>eg: `code`  
Horizontal Rule | To split blocks of texts visually we use 3 or more hyphens/asterisks/underscore <br>eg ---  
Link | Wrap link text in brackets [ ], and then wrap the URL in parentheses ( ) <br>eg: [title](https://www.example.com)
Image | Start with ! followed by alt text in [] and URl in () <br>eg: ![alt text](image.jpg)


---
---
# **DAY 3**

<h2><span style="color:lightblue">What is Terraform? :thinking:</span> </h2> 

HashiCorp Terraform is an infrastructure as code tool that lets you define both cloud and on-prem resources in human-readable configuration files that you can version, reuse, and share. It is a tool for building, changing, and versioning infrastructure safely and efficiently. Terraform can manage existing, popular service providers and custom in-house solutions.

Terraform can manage low-level components like compute, storage, and networking resources, as well as high-level components like DNS entries and SaaS features.

 Terraform is simply a tool to automate the deployment and management of infrastructure. 

It is an open‑source project maintained by HashiCorp. 

There are paid versions of Terraform available as either Terraform Cloud _(Terraform Cloud builds on these features by managing Terraform runs in a consistent and reliable environment instead of on your local machine.It  also has a private registry for sharing your organization's Terraform modules and providers. Terraform Cloud helps you collaborate on each step of your infrastructure development process. For example, each time you plan a new change, your team can review and approve the plan before you apply it.)_ 

or 

Terraform Enterprise. _(Terraform Enterprise is our self-hosted distribution of Terraform Cloud. It offers enterprises a private instance of the Terraform Cloud application, with no resource limits and with additional enterprise-grade architectural features like audit logging and SAML single sign-on.)_

 Terraform is also a vendor agnostic, meaning it doesn't prefer any particular cloud or service. You can use it against AWS, Azure, DigitalOcean, VMware, etc.Pretty much any infrastructure service you can think of probably works with Terraform. 

  You are describing how you want the world to be, and Terraform is in charge of handling the heavy lifting. The actual configuration files are written in either HashiCorp Configuration Language, a derivative of JSON, or in JSON directly.

---
<h2><span style="color:lightblue">What is Infrastructure as code?? :thinking:</span> </h2>

Infrastructure as code is provisioning infrastructure through software to achieve consistent and predictable environments. 
 It's not a manual process. And the goal is to achieve consistency. That means every time you use this software to deploy infrastructure, it does it in a consistent way and that the environment you get at the end is a predictable environment. It doesn't leave you guessing. It's going to look exactly like the configuration files say it should look. 
 
 That's very important, especially when you have multiple environments that will be running the same version of an application.


 You're going to be creating files using some sort of software and coding mechanism to define your infrastructure, and whether that format is JSON, YAML, or HashiCorp configuration language, infrastructure as code is going to be defined in code.

 Your infrastructure that you've defined in code should be stored in a versioned source control repository.

---
<h2><span style="color:lightblue">Why do we use terraform? :thinking:</span> </h2>

1. The Terraform language is declarative, describing an intended goal rather than the steps to reach that goal.

lets take an example

Now let's say in a declarative world I want software to make me a taco. That software is going to have a rudimentary idea of how to make food, kind of like a cook. Just like I can tell a cook I want a taco with the following toppings, I can use a configuration language like HashiCorp Configuration Language to declare what I want. 

In this case, I'm telling it I want something that is of type food and of the sub‑type taco, and I'm going to give it a name I can refer to it with, in this case bean‑taco. And then within my configuration block, I'm going to tell it the ingredients I want in my taco; beans, cheese, lettuce, and salsa. And that's all I have to tell the software. 

It already has a predefined routine for how to get ingredients and it has a predefined order in which to assemble those ingredients. 

If I want to change the defaults, I might put additional information in this configuration block, but the idea here is I'm declaring what I want. 

I want a bean taco with these ingredients, and then I'm leaving it up to the software to figure out exactly how to implement what I want. 

Terraform is an example of a declarative approach to deploying Infrastructure as Code.


2. Terraform is idempotence in nature.But what does idempotence mean?

lets take an example.

Let's say my niece, who also loves tacos, has asked me to make her a taco, and I do it. I say, "Here's your taco." Now, in an idempotent world, if she asks me again to make her a taco, I will go, "Um, you already have a taco." I'm not going to go ahead and make another taco because I'm aware of her state and the fact she already has a taco. 

If she gives me the same instruction again, I'm not going to do anything because her instruction already matches the state of the world she wants. She has the taco. 

In a non‑idempotent world, each time she told me to make her a taco, I would make and give her another taco. 

Terraform attempts to be idempotent in the sense that if you haven't changed anything about your code and you apply it again to the same environment, nothing will change in the environment because your defined code matches the reality of the infrastructure that exists.

3. Terraform can create configuration file templates to define, provision, and configure ECS resources in a repeatable and predictable manner, reducing deployment and management errors resulting from human intervention. 

---

 <h2><span style="color:lightblue">How to install terraform?:thinking:</span> </h2>
Installing Terraform is exceedingly simple. You simply download the executable compiled for your operating system, make sure that it's added to your path variable, and start using Terraform.
The first thing you're going to need to do is install Terraform if you don't already have it, and you can get it if you go to terraform.io/downloads.

If you're using macOS, you can use Homebrew, and if you're using Windows, you could use Chocolatey to install Terraform. 
You can follow the link for steps to download:

[Click here for steps on how to download terraform ](https://learn.hashicorp.com/tutorials/terraform/install-cli)

---
 <h2><span style="color:lightblue">Object types in Terraform :thinking:</span> </h2>
A block is a container for other content

There are three terraform object types we need to know about:

- ### __Providers:__ 
Provider blocks define information about a provider you want to use. For instance, we are going to be using the AWS provider and that provider wants to know what AWS account and region you're going to be using

- ### __Resources:__
Resources are things you want to create in a target environment and they are the bulk of what you'll be writing. Each resource is associated with a provider and will usually require some additional information for a configuration. A resource could be an EC2 instance, a virtual network, or even a database.

- ### __Data Sources:__
Data sources are a way to query information from a provider. You aren't creating anything, you're simply asking for information you might want to use in your configuration. 

Just like resources, data sources are associated with a provider. A data source could be a current list of availability zones in a region, an AMI to use for an EC2 instance, or a list of templates on a vSphere cluster.

###  __GENERAL BLOCK SYNTAX:__

```
block_type "label" "name_label"{
  key = "value"
  nested_block{
    key = "value
  }
}
```

Each block is going to start with the block type keyword that describes what type of object is being described in the block. 

Next is going to be a series of labels that are dependent on what type of object we're working with. 

The last label in the series is usually the name label, which provides a way to refer back to the object in the rest of the configuration.

Within that block, we are going to have one or more key value pairs that make use of available arguments for the object type. Each key will be a string and the value could be any of Terraform's different data types.

You can also have nested blocks inside of the main block. Nested blocks will start with the name of the nested block and curly braces. Inside the nested block will be more key value pairs.
 
 eg: 

 __Provider Block__
 
 ```
 provider "aws"{
  region="us-east-1"
 }
 ```
 eg:

__Resource Block__
 ```
 resources "aws_instance" "web_server"{
name = "web-server"
ebs_volume {
  size = 40
}
}
```

__Object Reference:__

<resource_type>.<name_label>.<attribute>

eg:

`aws_instance.web_server.name`

eg:

__Data Block__

```
data "aws_vpc" "selected" {
  id = var.vpc_id
}
```

___NOTE: Comments in HCL are given by '#' sign.___

---

### __What is terraform state?__
Terraform stores information about your infrastructure in a state file. This state file keeps track of resources created by your configuration and maps them to real-world resources.

Terraform compares your configuration with the state file and your existing infrastructure to create plans and make changes to your infrastructure.

When you apply terraform commands against your initialized configuration, Terraform writes metadata about your configuration to the state file and updates your infrastructure resources accordingly.

---
<h2><span style="color:lightblue">Workflow of Terraform :thinking:</span> </h2>
The core Terraform workflow consists of three stages:

- __Write:__ You define resources, which may be across multiple cloud providers and services. For example, you might create a configuration to deploy an application on virtual machines in a Virtual Private Cloud (VPC) network with security groups and a load balancer.

- __Plan:__ Terraform creates an execution plan describing the infrastructure it will create, update, or destroy based on the existing infrastructure and your configuration.

- __Apply:__ On approval, Terraform performs the proposed operations in the correct order, respecting any resource dependencies. For example, if you update the properties of a VPC and change the number of virtual machines in that VPC, Terraform will recreate the VPC before scaling the virtual machines.

![write](https://content.hashicorp.com/api/assets?product=terraform&version=refs%2Fheads%2Fv1.2&asset=website%2Fimg%2Fdocs%2Fintro-terraform-workflow.png&width=2048&height=1798)

---
## __Important Commands:__


Terraform makes use of provider plugins to interact with services like AWS. Before it can use those plugins, it needs to get them. This is done as part of the initialization process.

> `Terraform Init`:

Terraform init looks for configuration files inside of the current working directory and examines them to see if they need any provider plugins. If they do, it will try and download those plugins from the public Terraform Registry, unless you specify an alternate location. 

Terraform will also need to store state data about your configuration somewhere. 

Once initialization is complete, Terraform is ready to deploy some infrastructure.
![init](/Images/Images/init.PNG)

The next step in the workflow is to plan out your deployment with terraform plan. In this case, Terraform will take a look at your current configuration, the contents of your state data, determine the differences between the two, and make a plan to update your target environment to match the desired configuration. 

> `terraform plan`:

Terraform will print out the plan for you to look at, and you can verify the changes Terraform wants to make. You don't have to run a terraform plan, but it is pretty useful to know what Terraform is planning to do before it does it.

![plan](/Images/plan.PNG)

It's now time to actually make changes in the target environment, and you do that by running terraform apply.  Terraform will simply execute those changes using the provider plugins. The resources will be created or modified in the target environment, and then the state data will be updated to reflect the changes.

>`terraform apply` :
![apply](/Images/apply-cmd.PNG)

Lastly, If you are done with the environment, the command terraform destroy will do exactly that, destroy everything in the target environment based off of what is in state data. This is a dangerous command, and Terraform will ask you if you're sure.

>`terraform destroy` : 
![destroy](/Images/destroy-cmd.PNG)

___NOTE:Terraform will prompt you to enter a value after apply & destroy to get your confirmation to carry ahead with the tasks___

---
## __Other Commands in terraform__ 

>`terraform fmt` :
- Format your Terraform configuration files using the HCL language standard.
![fmt](/Images/fmt.PNG)

>`terraform validate` : 
- Validates the configuration files in your directory, and does not access any remote state or services. terraform init should be run before this command.
![validate](/Images/validate.PNG)

>`terraform show`: 
- Shows the state file in a human-readable format.
![show](/Images/show.PNG)

>`terraform state list` : 
- Lists out all the resources that are tracked in the current state file.
![state](/Images/state-list.PNG)

>`terraform providers` : - Displays a tree of providers used in the configuration files and their requirements.
![providers](/Images/providers.PNG)

>`terraform workspace list`:
- Workspaces can be useful when an engineer wants to test a slightly different version of the code. 
workspace list will list your workspaces.
![ws list](/Images/ws%20list.PNG)

>`terraform workspace show`:  
- Show the name of the current workspace.
![ws show](/Images/ws%20show.PNG)

>`terraform output` :  
- Lists all the outputs currently held in your state file. These are displayed by default at the end of a terraform apply, this command can be useful if you want to view them independently.
![output](/Images/output.PNG)

>`terraform graph` :  
- Produces a graph in DOT language showing the dependencies between objects in the state file. This can then be rendered by a program called Graphwiz (amongst others).
![graph](/Images/graph.PNG)

>`terraform console` :  
- Allows testing and exploration of expressions on the interactive console using the command line
![console](/Images/console.PNG)

---
## __WORKING WITH DATA IN TERRAFORM:__ 

Terraform can accept values as input, transform values inside a configuration, and return values as output. 

1. The first is called input variables, or just variables for short. Input variables are used to pass information to a Terraform configuration. <br>The variables are defined inside the configuration, and the values are supplied when Terraform is executed. 

2. Local values, sometimes just called locals, are computed values inside the configuration that can be referenced throughout the config. In other programming languages, these would usually be called variables. The values for locals are not submitted directly from an external input, but they can be computed based on input variables and internal references.

3. Data is returned by Terraform with output values. The outputs are defined in the configuration, and the value of each output will depend on what it references inside the configuration.

---
## INPUT VARIABLES SYNTAX:

A variable block starts with the variable keyword followed by a single label, that is the name label. 

All the other properties of the variable are defined inside the block and all of those properties are optional.

Let's take a look at the optional arguments inside the variable block. 
- The type argument defines the data type associated with your variable and it provides a certain level of error checking. If you say the variables should be a number and someone submits a string, Terraform will throw an error. 
- The description argument helps provide some context for the user when they get an error. 
- The default argument allows you to set a default value for the variable. If no value is submitted for the variable, Terraform will use this default value. If you don't set a default value and none is submitted when the configuration is invoked, Terraform will prompt you at the command line to supply a value. 
- The last argument is the sensitive argument. It accepts a Boolean value of true or false.
  - If it's set to true, Terraform will not show the value of the variable in its logs or the terminal output. This argument is useful when you have to submit potentially sensitive values like a password or an API key and you don't want them showing up in clear text in your logs or terminal output.

### __SYNTAX:__
> `variable "name_label"{} `

 or 
 ```
 variable "name_label" {
  type = "value"
  description = "value"
  default = "value"
  sensitive = true | false
 }
 ```

eg:

> `variable "billing_tag" {}`

or
```
variable "aws_region"{
  type=string
  description = "Region to use for AWS resources"
  default = "us-east-1"
  sensitive  = false
}
```

__Variable Reference:__

`var.<name_label>`

eg:

`var.aws_region`

---
## LOCALS

local values are values computed inside of the configuration. You can't submit values directly to them, unlike input variables. 

The syntax for locals starts with the keyword locals, and that's it for labels on the block. The rest of the information goes inside of the block. 

Inside the block are key value pairs. The value can be any supported Terraform data type, string, list, object, the sky is the limit, or more accurately, the supported data types are the limit.

___Note:
 You can specify the locals block multiple times in your configuration if you want to, but the name of each key must be unique within the configuration since that is how you reference a locals value___

### __SYNTAX:__
```
locals {<BR>
  key = value
}
```

eg:

```
locals {<BR>
  service_name = "forum"<BR>
  comman_tags{<BR>
    country = "India"
    state = "Maharastra"
  <BR>}
<BR>}
```

__locals reference:__
 
`local.<name_label>`

eg:

`local.service_name`

`local.comman_tags.state`

---
## OUTPUT

Output values are how we get information out of Terraform. Outputs are printed out to the terminal window at the end of a configuration run.

The syntax for an output starts with the output keyword followed by the name_label for the output. Inside the configuration block, the only required argument is the value of the output.

The value of an output can be any supported Terraform data type. You can return a simple string or a complex object. 

Optional arguments include the description, which is only seen when looking at the code for a configuration.

The sensitive argument will set an output to sensitive, meaning that the actual value will not be printed in the terminal. 

### __SYNTAX:__
```
output "name_label"{
  value = output_value
  description = "Description of output"
  sensitive = true|false
}
```

eg:
```
output "public_dns_hostname"{
  value = aws_instance.web_server.public_dns
  description = "Public DNS instance web server"
}
```

---
## __SUPPLY VARIABLE VALUES__

When it comes to setting the value for a variable, there are at least six ways of doing so.

1. The easiest way to set a value is to set the value with the default argument. 

2. You can use the ‑var flag followed by the name of the variable and the value you want to set it equal to. You can repeat this flag for each variable you'd like to set. 
![var](https://miro.medium.com/max/1050/1*kxVb0o9hDyex_obYq-4UAw.png)
3. You can also have all your variable values in a file and submit that file with the ‑var‑file argument. Inside the file will be each variable name label as a key, followed by an equal sign and the value for the variable. 

There are two other ways to submit values from a file. 
- 4  If there is a file in the same directory as the configuration named terraform.tfvars or terraform.tfvars.json, which needs to be properly formatted JSON, Terraform will use the values it finds in that file. 
- 5  Additionally, if there is a file in the same directory as the configuration ending in .auto.tfvars or .auto.tfvars.json, Terraform will use those values as well. 

![file](https://miro.medium.com/max/1050/1*9fWArk6W7IrfoL-S6zr3ew.png)

6. The final option is to use environment variables. <br>Terraform will look for any environment variables that start with TF_VAR_ followed by the variable name. 
![env](https://jeffbrown.tech/wp-content/uploads/2021/07/input-variable-example-1024x580.png)


If you don't submit a value for a variable in any of these ways,Terraform will prompt you for a value at runtime. 
![no value](https://i0.wp.com/blog.knoldus.com/wp-content/uploads/2022/01/Screenshot-from-2022-01-01-23-48-20.png?w=1004&ssl=1) 

There is an order of precedence. 
![order](https://i0.wp.com/blog.knoldus.com/wp-content/uploads/2022/01/Untitled-Diagram.drawio.png?ssl=1)

---
## __Lifecycle rules:__

lifecycle is a nested block that can appear within a resource block.

The arguments available within a lifecycle block are create_before_destroy, prevent_destroy, ignore_changes

- The create_before_destroy meta-argument changes this behavior so that the new replacement object is created first, and the prior object is destroyed after the replacement is created.
`create_before_destroy = true|false`

- prevent_destroy (bool) - This meta-argument, when set to true, will cause Terraform to reject with an error any plan that would destroy the object associated with the resource.
`prevent_destroy = true|false`

- ignore_changes (list of attribute names) - By default, Terraform detects any difference in the current settings of a real infrastructure object and plans to update the remote object to match configuration.
ignore_changes = [name , region] or
ignore_changes = all

---
## __Provisioners:__

Provisioners are used to execute scripts on a local or remote machine as part of resource creation or destruction. 

Provisioners can be used to bootstrap a resource, cleanup before destroy, run configuration management, etc.

### __SYNTAX:__

You can add a provisioner block inside the resource block of a compute instance

```
resource "" ""{
provisioner "type"{
  key = "value"
}
}
```

__File provisioner:__

The file provisioner is used to copy files or directories from the machine executing the terraform apply to the newly created resource. 

The file provisioner can connect to the resource using either ssh or winrm connections.

__Syntax:__

eg: 
```
resource "aws_instance" "web" {
  # ...

  # Copies the myapp.conf file to /etc/myapp.conf
  provisioner "file" {
    source      = "conf/myapp.conf"
    destination = "/etc/myapp.conf"
  }
}
```

__local-exec:__

The local-exec provisioner invokes a local executable after a resource is created. This invokes a process on the machine running Terraform, not on the resource.

Basically, this provisioner is used when you want to perform some tasks onto your local machine where you have installed the terraform. 

So local-exec provisioner is never used to perform any task on the remote machine. It will always be used to perform local operations onto your local machine.

__Syntax:__

eg:
```
resource "aws_instance" "web"{
  provisioner "local-exec"{
    command = "echo first"
    on_failure = continue | fail 
  }
}
```
By default, provisioners that fail will also cause the Terraform apply itself to fail. The on_failure setting can be used to change this. The allowed values are:

- continue - Ignore the error and continue with creation or destruction.

- fail - Raise an error and stop applying (the default behavior). If this is a creation provisioner, taint the resource._

__Remote-exec:__

The remote-exec provisioner invokes a script on a remote resource after it is created. As the name suggests remote-exec provisioner is always going to work on the remote machine. 

With the help of this, you can specify the commands of shell scripts that want to execute on the remote machine. The remote-exec provisioner invokes a script on a remote resource after it is created. This can be used to run a configuration management tool, bootstrap into a cluster, etc. It requires a connection and supports both ssh and winrm.

It contains a connection block which helps to login to server for provisioning work.

__Syntax:__
eg:
```
connection{
  type = "ssh"|"winrm"
  host = 
  user = ""
  password/private_key=""
}
```
eg:
```
resource "aws_instance" "web" {
  connection {
    type     = "ssh" _connection type that should be used_
    user     = "root" _Defaults to root for type ssh and defaults to administrator for type winrm_
    password = var.root_password _The password we should use for the connection_
    host     = self.public_ip _The address of the resource to connect to._
  }
  provisioner "remote-exec" {
    inline = [
      "puppet apply",
      "consul join ${aws_instance.web.private_ip}",
    ]
  }
}
```

---

__NULL Resources:__

If you need to run provisioners that aren't directly associated with a specific resource, you can associate them with a null_resource.

Instances of null resource are treated like normal resources, but they don't do anything.
Like with any other resource, you can configure provisioners and connection details on a nulL resource.

__triggers__ : A map of values which should cause this set of provisioners to re-run. Values are meant to be interpolated references to variables or attributes of other resources.

![null](https://i.ytimg.com/vi/TVOgBUK67IY/maxresdefault.jpg)

---

<h2><span style="color:lightblue">Data Types in Terraform :thinking:</span> </h2>
We can group the data types supported by Terraform into three categories. 

- The most basic are the primitive data types. <br>These are string, number, and Boolean. A string is a sequence of Unicode characters, a number can be an integer or a decimal, and Boolean is either true or false. eg."Omshree", "Terraform", 7, 100.2.

- The next category is collection data types, and they represent a grouping of the primitive data types.<br> A list is an ordered group of elements, a set is an an unordered group of elements, and a map is a group of key‑value pairs.<br> In each case, the values stored in any of these collection data types must be of the __same data type.__

- The last group is structural data types, and they're very similar to collection data types, except they allow you to __mix the data types stored__ in each grouping. <br>Aside from that difference, tuples are functionally equivalent to lists and objects are basically equivalent to maps.

eg:

---
| Name | Example | Reference Collection Values 
| ------- | ----------- | ----------|
List(ordered and allows duplicate value) | [1,2,3,4,4] <br> ["hi" , "hey" "hello"] |var.<name_label>[<element_number>]
Tuple | tuple([string, number , bool])<br>tuple(["Hi",99.0,true])
Set(unordered and doesn't allow duplicate values) | [1.2.3.4]<br> ["hi","bye"]
Map (Key = "value")|  {  <br> small = "t2.micro" <br>  medium = "t2.small" <br>  large = "t2.large"<br>}| var.<name_label>.<key_name> or <br> var.<name_label>["key_name"]
Object | list(object(<br>{<br>name = string<br> age = number<br>}<br>)<br>) | var.<object_name>
---

---
# **DAY 4**

---
<h2><span style="color:lightblue">What is Terraform Landing Zone? :thinking:</span> </h2> 

The Terraform Landing Zone has been built to provide an automated Landing Zone capable of being deployed to a new AWS account enabling Customer’s infrastructure (networking, compute, storage), operations, security, and governance requirements for given applications that sit inside AWS account. It also supports future workloads such as the building of new applications and the migration of existing applications, if required.

An AWS Landing Zone refers to the foundational services created within an AWS account before deploying any workloads.

---
__What is mkdocs runbook?__
MkDocs is a fast, simple and downright gorgeous static site generator that's geared towards building project documentation. Documentation source files are written in Markdown, and configured with a single YAML configuration file. 

---
### __Overview__

The TLZ Accelerator is made up of three distinct areas referred to as Account Vending Machine (AVM), Terraform Enterprise (TFE), Core Account Structure
- ### Account Vending Machine(AVM) 
<br>Starting point for Account Creation and expected to be integrated into existing Request Management tooling or Service Catalog.

It takes care of initial provisioning of account and automating cross-account activities that while possible in Terraform are more adept to being executed using standard AWS services such as Lambda Invokes and Provisions 3rd-party tooling such as TFE and VCS tooling

- ### Terraform Enterprise(TFE)

Provisions all the necessary setting and services to provide the “baseline” of an account. It is triggered from the AVM.

Baseline is invoked from a template and allows for customization per account if necessary
Leverages Module capabilities of Terraform

- ### Core Account Structure

---
## __AWS Account Structure__:

The AWS accounts are grouped into an AWS Organization. The organization consists of six core accounts, and then as many project/application accounts as desired, grouped by organizational unit.

__Organizational units__ provide an optional mechanism for grouping accounts into logical collections. AWS Service Control Policies can be attached to organizational units which control which actions are allowed within the AWS accounts assigned to that unit.

For example, it may be desirable to prevent users within application accounts from purchasing reserved instances as these are best purchased in the master account so they can be shared across application accounts in future.

![img](http://d1kkhzkm4nk5kw.cloudfront.net/images/aws_account_structure.png)

By Default there are 4OUs:
- Core: This OU houses all administrative accounts, such as the core landing zone accounts; logging, security, shared services, infra-shared services and network. No application accounts should be launched into this OU

- Application: Application accounts are broken into two types
  - Production: Production Accounts will be within this OU and this includes PRD and pre-PRD.
  - Non-Production: Non-production accounts will be created under this OU and includes Dev, QA, STG etc.

- Sandbox: Sandbox accounts are created in this OU.

---
## __CORE ACCOUNTS__

1. __MASTER PAYER__: <br>The Master Payer AWS Account is the highest privileged AWS account in an AWS Organization and has the ability to manage, move, and apply policies to all sub AWS accounts in the Organization.
<br>The master account is also used for extended account management activities including creating new accounts, grouping accounts into organizational units, and assigning Service Control Policies (SCPs)

2. __Loggin and Audit Account__:<br>
The purpose of the logging and audit account is to provide a central aggregation and secure storage point for all audit logs created within the AWS Organization. This account is centralized location for copies of every account’s Audit and Configuration compliance logs.

3. __Security Account:__<br>The Security account creates auditor (read-only) and administrator (full-access) cross-account roles from a Security account to all AWS Landing Zone managed accounts. <br>The intent of these roles is to be used by security and compliance teams to audit, such as hosting custom AWS Config Rule lambda functions, or perform automated security operations, such as perform remediation actions. As a result, we strongly recommend that this account be restricted to authorized security and compliance personnel, and related security or audit tools.

4. __Shared-Services:__<br> This is the centralized account for shared-services used by all accounts under master-payer account.

5. __Networking Account:__<br> The Network account is a core account dedicated for enabling network traffic between AWS VPCs within the organization. This account contains:

6. __Break Glass:__<br>
Break glass  refers to a quick means for a person who does not have access privileges to certain information to gain access when necessary.

---
<h2><span style="color:lightblue">What is Service Control Policies? :thinking:</span> </h2> 

Organization administrators have the ability to manage AWS Account OU placement and Service Control Policies (SCP) for all accounts within the Organization. This includes but is not limited to add/remove accounts within the Organization, move accounts to different Organizational Unites (OU's), apply account-level Service Control Policies (SCP), etc. Administrative access in the Master AWS Account grants the ability to assume an IAM Role, which grants access into child AWS accounts.

Service control policies must be version controlled and follow an InfoSec approved change management process

---
---
# **DAY 5**
<h2><span style="color:lightblue">What is GCP(Google Cloud Platform? :thinking:</span> </h2> 

GCP is a public cloud vendor that offers a suite of computing services to do everything from data management to delivering web and video over the web to AI and machine learning tools. Customers are able to access computer resources housed in Google’s data centers around the world for free or on a pay-per-use basis.

The cloud infrastructure of GCP is built around:

- Multi-regions – a large geographic area, such as the United States, that contains two or more geographic places

- Regions – are collections of zones that provide high-bandwidth, low-latency network connections to other zones in the same region.

- Zones – is an isolated location within a region and is composed of several physical infrastructures housed in a data center called cluster.


---
## __IAM__
Identity and Access Management (IAM) is the process of managing _who_ can do _what_ on _which_ resources.

- Basically who could be the user/groups/service account

- what is roles/actions they can perform eg: view/edit

- which specifies the resource they can do the action on eg s3,vm etc.

IAM lets you set policies at the following levels of the resource hierarchy:

- __Organization level__ : <br>The organization resource represents your company.
IAM roles granted at this level are inherited by all resources under the organization.

- __Folder level__ :<br> Folders can contain projects, other folders, or a combination of both. Roles granted at the highest folder level will be inherited by projects or other folders that are contained in that parent folder.

- __Project level:__ <br> Projects represent a trust boundary within your company.
Services within the same project have a default level of trust. For example, App Engine instances can access Cloud Storage buckets within the same project.

IAM roles granted at the project level are inherited by resources within that project.

- __Resource level:__ <br> Grant certain users permission to a single resource within a project.

![img](https://www.freecodecamp.org/news/content/images/2020/10/resource-manager.png)


---
## ROLES
A role contains a set of permissions that allows you to perform specific actions on Google Cloud resources.
You don’t directly grant users permissions in IAM. Instead, you grant them roles, which bundle one or more permissions.

There are three types of roles in Google Cloud IAM:
- __Basic Roles:__

Includes Owner, Editor, and Viewer role that existed prior to the introduction of IAM.
- __Predefined Roles:__

Provides granular access for a specific service and is managed and defined by Google Cloud. Prevents unwanted access to other resources. Google is responsible for updating and adding permissions as necessary.
- __Custom Roles:__

Provides granular access according to a user-defined list of permissions.
You can create a custom IAM role with one or more permissions and then grant that custom role to users or groups.
Custom roles are not maintained by Google. You can grant multiple roles to a user or a group.

___Note: Enforce least privilege at all times.___

---
## __Custom Roles__

Custom roles are similar to predefined roles, but they are created and managed by users directly. Typically you can create custom roles at the organization or a project level, by selecting the list of permissions it should have.

In support of the principle of least privilege, a custom role will only have permissions that are granted at the level at which it was created. For example, a custom role created at the project level will not have the same permissions that are only available at the organizational level, and vice versa.

---
## __SERVICE ACCOUNTS__
A service account is a special kind of account used by an application or a virtual machine (VM) instance, not a person.
Applications use service accounts to make authorized API calls, authorized as either:
  - the service account itself
  - as Google Workspace
  - as Cloud Identity users through domain-wide delegation

A service account is identified by its email address, which is unique to the account.
service-account-name@project-id.iam.gserviceaccount.com
Each service account is associated with two sets of public/private RSA key pairs used to authenticate to Google.

### Types of service accounts:
  - User-managed service accounts
  - Default service accounts

Google creates a user-managed service account when you use Google Cloud services. These accounts are called default service accounts.

The default service accounts help you get started with Google Cloud services quickly.

In addition to being an identity, a service account is also a resource with IAM policies attached to it, which means you can define who can use the account and who can perform specific actions on the service account.

---

## __Pub/Sub__
Pub/Sub is Google's fully-managed message queue, allowing you to decouple publishers (adding messages to the queue) and subscribers (consuming messages from the queue).

Core Concepts:

  - Topic: A named resource to which messages are sent by publishers.

  - Subscription: A named resource representing the stream of messages from a single, specific topic, to be delivered to the subscribing application.
  
  - Message: The combination of data and (optional) attributes that a publisher sends to a topic and is eventually delivered to subscribers.

  - Message attribute: A key-value pair that a publisher can define for a message. For example, key iana.org/language_tag and value en could be added to messages to mark them as readable by an English-speaking subscriber.
  
  - Publisher: An application that creates and sends messages to a single or multiple topics.
  - Subscriber: An application with a subscription to a single or multiple topics to receive messages from it.
  - Acknowledgment (or "ack"): A signal sent by a subscriber to Pub/Sub after it has received a message successfully.   Acknowledged messages are removed from the subscription message queue.

Push and pull: The two message delivery methods. A subscriber receives messages either by Pub/Sub pushing them to the subscriber chosen endpoint, or by the subscriber pulling them from the service.
  - Push: Messages are sent to subscribers, resulting in lower latency.
  - Pull: Subscribers pull messages from topics, better suited for a large volume of messages.

---
## How does Pub/Sub work?
![work](https://k21academy.com/wp-content/uploads/2021/05/Intro-to-Google-Cloud-Pub-Sub2__1_.gif)

1. A publisher application creates a topic in the Publisher/Subscriber service and sends messages to the topic. The message comprises a payload and optional attributes describing the payload content.
2. The service makes sure that published messages are retained on behalf of the subscriptions. The message published is retained for a subscription till it is acknowledged by a subscriber consuming messages from that particular subscription.
3. Pub/Sub forwards messages individually from a topic to all of its subscriptions.
4. A subscriber receives messages either by Pub/Sub pushing them to the subscriber’s chosen endpoint or by the subscriber pulling them from the service.
5. An acknowledgment is sent by the subscriber to the Pub/Sub service for each received message.
6. The service then removes acknowledged messages from the subscription’s message queue.

Publisher-subscriber relationships can be:

  - Many to Many:

![img](https://k21academy.com/wp-content/uploads/2021/05/ManytoOne_Diagram-04-686x1024.png)

  - One to Many(fan out):

When there are 2 subscribers X amd Y they want to recievr message from Publisher A. They will subscribe to subscription X and Y to get the message via Topic A.
![img](https://k21academy.com/wp-content/uploads/2021/05/ManytoOne_Diagram-05.png)

  - Many to One(fan in):

Suppose Subscriber X wants to recieve message from Publisher A and B, which will create 2 topics Topic A AND B. Subscriber X will subscribe to the subscriptions created by A and B and recieve the message through them.

![img](https://k21academy.com/wp-content/uploads/2021/05/ManytoOne_Diagram-03.png)

---
## __Datastore__

Datastore is a completely no-ops, highly-scalable document database ideal for web and mobile applications: game states, product catalogs, real-time inventory, and so on. 

It is a schemaless database, which allows you to worry less about making changes to your underlying data structure as your application evolves. Datastore provides a powerful query engine that allows you to search for data across multiple properties and sort as needed.


---
## __BigQuery__
BigQuery is Google's serverless data warehousing and provides analytics capabilities for petabyte-scale databases.
BigQuery automatically backs up your tables, but you can always export them to GCS to be on the safe side - incurring extra costs.

Data can be ingested in batches (for instance, from a GCS bucket) or from a stream in multiple formats: CSV, JSON. Also, you can query data that resides in external sources, called federated sources, for example, GCS buckets.

You can interact with your data in BigQuery using SQL via the:
  
  - Google Console.

  - Command-line, running commands like bq query 'SELECT field FROM ....

  - REST API.

  - Code using client libraries.

User-Defined Functions allow you to combine SQL queries with JavaScript functions to create complex operations.

BigQuery is a columnar data store: records are stored in columns. Tables are collections of columns and datasets are collections of tables.

Jobs are actions to load, export, query, or copy data that BigQuery runs on your behalf.

Views are virtual tables defined by a SQL query and are useful sharing data with others when you want to control exactly what they have access to.

Your costs depend on how much data you store and stream into BigQuery and how much data you query. 

---
## __KEY MANAGERMENT SYSTEM(KMS)__
Key Management System (KMS) – KMS is a centralized cloud key management service that can use a key to encrypt, decrypt, or sign data such as secrets for storage. Meanwhile, the keys you manage externally with an external key management partner can be used via Cloud EKM.

Google KMS is the service that allows you to manage your encryption keys. You can create, rotate, and destroy symmetric encryption keys. All keys related activity is registered in logs. These keys are referred to as customer-managed encryption keys.

---
## __SECRET MANAGER__
Secret Manager is a secure and convenient storage system for API keys, passwords, certificates, and other sensitive data. Secret Manager provides a central place and single source of truth to manage, access, and audit secrets across Google Cloud.
A secret is a project-global object that contains a collection of metadata and secret versions. The metadata can include replication locations, labels, annotations, and permissions. The secret versions store the actual secret data, such as an API key or credential.

A secret version stores the actual secret data, such as API keys, passwords, or certificates.
You can address individual versions of a secret. You cannot modify a version, but you can delete it.

You rotate a secret by adding a new secret version to the secret. Any version of a given secret can be accessed, as long as that version is enabled. To prevent a secret version from being used, you can disable that version.

---
## __DIALOGFLOW__
Dialogflow is an NLP (Natural Language Processing) platform, which is used to develop an application related to the conversations and experience for the customers of the company in different languages on numerous platforms.
Dialogflow is mainly used to build actions for most of the Google Assistant devices.
The Dialogflow is an intuitive and user-friendly tool that includes Google's machine learning expertise and some Google products such as Google Cloud Speech-to-Text.

__Agents__

The Dialogflow agent is defined as a virtual agent whose task is to manage the end-user conversations. An agent is a module that can understand the complexities of the human language. During a conversation, the Dialogflow converts the text of end-user or audio into the structured data so that your applications can understand this. The Dialogflow agent is designed to manage the kinds of conversation your system needs.

The Dialogflow agent is the same as an agent in a human call center. Both are trained to handle the conversation scenario and don't need to be over explicit in their training,

__Intents__

An intent classifies the intention of an end-user for one conversation turn. For every agent, we have to define various users, and our combined agent is capable of handling an entire conversation. At the time, when the end-user says or writes something which is denoted as end-user expression, then the Dialogflow check and matches the end-user expression to your agent's best intent. Intent matching is also called Intent Classification.

For example: If you need to make an agent for the weather, which has the capability to identify and respond to the queries of the end-users related to the weather. Then you have to define an intent for the weather forecasting questions. When an end-user asks, "what is the forecast?" then the Dialogflow check and match the end-user expression to the intent of the forecast. If we want to obtain the essential information from the end-user expression such as location, time for the weather forecast according to our desire, then we have to define our intent. The obtained information is essential to the system for performing the queries related to the system.

The following things are comprised in the basic intent:

1. Training Phrases: - Training phrases means an example phrases for what the end-users can say. If one of these phrases resembles an end-user expression, then the Dialogflow matches the intent. There is no need to define each possible example as the built-in machine learning of Dialogflow expands with other related phrases on your list.

2. Action: - For the agent, we can define an action. At the time, when we match an intent, then the Dialogflow gives the actions to the system, and the action can be used to trigger various actions that are already defined in the system.

3. Parameters: - At run time, if we want to match an intent then as a parameter the Dialogflow gives the value from the expressions of the end-user. Every parameter contains a type known as an entity type, and the entity type exactly dictates how data is retrieved. The parameters are not like raw input of end-user. Parameter means structured data, which is used to perform logic or produce responses.

4. Responses: - We can define speech, visual, or text replies to return to the end-user. These are able to give the answer to the end-user and also ask for more information to the end-user and can also terminate the conversation.

![img](https://static.javatpoint.com/tutorial/dialogflow/images/basics-of-dialogflow2.png)

__Entities__
There is a type of every intent parameter, which is known as an Entity type. The task performed by the end-user is to explain how data can be extracted from the end-user expression. The Dialogflow offers you a various system entity which are predefined, which is able to match various types of common data. For example, there are various types of system entities for matching email addresses, colors, time, date, etc. For matching custom data, we can also make our custom entities. For example: we can define a fruit entity that matches the kinds of the fruits which are available to buy with the agent of a grocery store.

__Context__
The context of Dialogflow is the same as a natural language context. When a person tells you, "they are blue," you have to grasp the context to know which they are referring to. In the same way, for Dialogflow, in order to handle an end-user expression, the Dialogflow context must be provided to match an intent appropriately.

To handle the flow of the conversation, contexts are used. By setting input and output contexts, that are recognized by the string names, we can configure the contexts for the intents. If the intent is matched, then for that intent, any configured output context will be active. When the contexts are in the active state then the Dialogflow try to match intent configured to the input contexts which is corresponding to the contexts which are presently active.

![img](https://static.javatpoint.com/tutorial/dialogflow/images/basics-of-dialogflow3.png)

__Follow-up Intents__

The Follow-up Intents can be used to create contexts automatically for the pairs of intents. A follow-up intent means a child of the intent of its associated parent. When the follow-up intent is created, then automatically an output context will be added to the parent intent, and in the follow-up intent, the input context having a similar name will be added. A follow-up intent is matched only in one situation, and the situation is, if the parent intent is in the turn of previous conversational. Multiple levels nested follow-up intents can also be created in the Dialogflow.

---
---
# **DAY 6**

<h2><span style="color:lightblue"> What is Agile Framework? :thinking: </span> </h2>

Agile is a project management approach developed as a more flexible and efficient way to get products to market. The word ‘agile’ refers to the ability to move quickly and easily. Therefore, an Agile approach enables project teams to adapt faster and easier compared to other project methodologies. 

The Agile methodology is a way to manage a project by breaking it up into several phases. It involves constant collaboration with stakeholders and continuous improvement at every stage. Once the work begins, teams cycle through a process of planning, executing, and evaluating. Continuous collaboration is vital, both with team members and project stakeholders.

Agile project management works off the basis that a project can be continuously improved upon throughout its life cycle, with changes being made quickly and responsively.

Agile's four main values are:

  - Individuals and interactions over processes and tools: <br>This gives a development centric/client centric environment. The people/end-users are given more importance.

  - Working software over comprehensive documentation:<br>Here the individual is more concerned about the application, how it works, how much it has developed rather than the internal documentation which could be 100-150 pages of codes on how the application was build. In short Development is given more importance than documentation.

  - Customer collaboration over contract negotiation:<br>Customer inputs/feedbacks matter during the production of the software/application

  - Responding to change over following a plan:<br>Agile works on feedback. Since the application has been divided in chunks so it gets easy to modify the changes.

Agile is one of the most popular approaches to project management due to its flexibility, adaptability to change, and high level of customer input. Agile model works in different iterations instead of huge chunk of application. 

Iterations are basically set of tasks that you have to work on in a particular sprint.

![agile](https://kruschecompany.com/wp-content/uploads/2021/06/AdobeStock_255546088-1280x595.png)

Agile has a high level of customer involvement and includes frequent reviews of progress with both the project team and the customer. 

---
<h2><span style="color:lightblue"> Who should use Agile Framework? :thinking: </span> </h2>

The benefits of Agile project management are many, particularly for the following organizations and project types:

- Any project that evolves or does not have clear scope and requirements at the start, 
- Organizations that work in a fast-changing environment, such as technology 
- Organizations that need to work closely with their customers and other external parties throughout the life of the project
- Companies that emphasize process and product improvement and are constantly looking to innovate
- Projects with many interdependent tasks, where the team needs to work closely and frequently communicate to ensure success 
- Projects that require rapid feedback from stakeholders about each product iteration before moving on to the next version or draft

---
<h2><span style="color:lightblue"> Benefits of adopting Agile method? :thinking: </span> </h2>

1. Continuous customer contact:
Traditional project management methods generally only had the project team in touch with the customer at the start and end of the project. If customer requirements or expectations were not captured correctly in the beginning or changed over time, the project team had no idea until it was too late.<br>
With Agile, there’s ongoing contact throughout the entire process and iterative deliveries to ensure your team is on track, so the end product will be exactly what the customer wants.

2. The ability to adapt :
What if your customer told you halfway through a project that they needed a scope change? Using a traditional approach to project management, this either couldn’t be accommodated or likely involved significant increases to both the project cost and schedule.
<br>With Agile, you can incorporate changes with minimal effort, no matter how far along in the project.   

3. Faster delivery:
Agile incorporates a continuous development approach that ensures your team is continuously delivering workable products. Instead of waiting for six to 12 months or longer for an end product, your client is getting a working version of the product at much shorter intervals, typically every two to four weeks. 

4. Lower project risk:
Your team is developing versions of the product regularly and getting customer feedback early on, minimizing the risk of a project failing. Breaking a large project into iterations reduces your risk of an iteration or draft failure. You’re more likely to find small problems early that can be addressed quickly, rather than discovering a large issue only at the time of final testing before the end delivery. If later you encounter a problem or need to cancel the project, you’ll have invested less time and money.

5. Ongoing innovation:
Agile supports collaboration and continuous improvement, both of which can lead to innovation and the development of new products and features. Co-locating teams and having daily meetings encourages brainstorming and idea creation. 
<br>Agile supports an “idea meritocracy” where the best idea wins out, no matter who it comes from. The project team, other stakeholders, and the customer can figure out functionality and features together. 

---
<h2><span style="color:lightblue"> Agile team: Key roles and responsibilities :thinking: </span> </h2>

An Agile team structure will commonly outline specific roles for each team member. While the focus is on a person’s skill set rather than their job title, a defined set of roles can create clarity in Agile workflows. 

Here are some of the key roles in an Agile team structure:
- __Team lead/Scrum Master__: <br> A team lead is responsible for coordinating the team and ensuring that processes run smoothly. They will organize incoming requests, manage tasks, monitor workflows, and host meetings. They will also ensure the team is following the principles as outlined in the Agile Manifesto. In Scrum, a team lead is known as a Scrum master. The Scrum master is responsible for arranging the daily meetings, improving team interactions, and maximizing productivity. <br>The Agile project manager’s roles and responsibilities often include the position of Scrum master. However, they can delegate this to anyone on the team who’s a Scrum expert and a strong facilitator. 

- __Product owner__: <br>A product owner represents the needs of the client. Their job is to clearly outline the customer requirements and ensure they are met throughout the Agile project life cycle. They will communicate regularly with the team, offering guidance on features to include and informing them of what needs to be prioritized. This person has the ultimate authority over the final product. The product owner’s job is to ensure product requirements, functionality, and priorities are understood and achieved.

- __Team member__:<br>Team member is a broad term that can denote a number of different roles across different industries. For example, an Agile development team will be made up of programmers, UX designers, software developers, and quality assurance testers. A digital marketing team, on the other hand, could include copywriters, editors, PPC managers, SEO specialists, and more. All of these people can be referred to as team members in an Agile team structure.

- __Stakeholder__:<br>A stakeholder is not directly involved in the project activities, but they play an important role in determining the final deliverables. Stakeholders will liaise regularly with the team lead, product owner, and team members to offer input into the development process. Their feedback could significantly influence the end result of the project. Stakeholder examples include end-users, investors, and senior company executives. 

---
<h2><span style="color:lightblue"> All about Sprints</span> </h2>

Scrum entails an iterative approach to project management. The Scrum methodology prescribes breaking a project down into sprints that typically only last one to four weeks. Each sprint ends with the completion of a workable version or draft of the final project deliverable. 

The sprint duration is always fixed. That ensures developers and users can regularly review the project’s direction and keep it on track. However, it also means that a project can run over schedule, unless developers decide to reduce its scope and ambition.


## __What is the sprint cycle?__

A sprint cycle is the repeatable process you’ll go through every time you manage and plan a sprint. The steps of the process will stay the same—what will change are the insights you learn at the end of a sprint and how you apply them to make the next sprint even more effective.

There are four stages that the project manager takes ownership of within each sprint, including sprint planning, check-ins, reviews, and retrospectives.

### __Sprint planning__:
Setting up a sprint requires proper sprint planning. The project manager gathers the team to determine how much work can be completed within one sprint. It’s important that there is enough work to fill the time span, but not too much. Not planning enough work can derail the project and lead to budget and timeline overages. Planning to accomplish too much can lead to team burnout and missed deadlines.

Ideally, your planning should take place in a centralized work management platform, like Workfront. Opt for a system that allows you to follow an Agile approach to your projects and offers a work board for hosting sprints and backlogged tasks.

### __Daily Scrum__:
Also known as stand-up meetings, daily Scrum meetings ensure sprints are running on schedule and all team members are in the loop when problems pop up. Sprint stand-ups typically only last 15 minutes and require each team member to discuss what they’ve accomplished since the last meeting, what they’ll work on before the next meeting, and if any obstacles are standing in their way.
Daily stand-ups should be quick touch points. If more in-depth meetings are required, they should be scheduled outside of stand-ups.

### __Sprint review:__
Once a sprint is completed, the project manager hosts a sprint review meeting with all team members and stakeholders to demonstrate sprint outputs, determine what was accomplished and what wasn’t, and review project forecasts. Untested or incomplete work is not shown, but is instead saved for the next sprint’s planning round.

### __Sprint retrospective:__
The final step in the sprint management process is the sprint retrospective. This takes place after the sprint review and before the next sprint planning session. This collaborative session allows team members to discuss accomplishments and challenges during the previous sprint so that processes can be altered, if needed. The goal is to fix one thing at a time and make small, incremental changes from sprint to sprint.

---
<h2><span style="color:lightblue"> What is SAFe? :thinking: </span> </h2>

SAFe stands for Scaled Agile Framework, and it is a knowledge base used by development teams to implement Agile principles into large organizations. It adjusts the best practices of Agile project management to make the methodology work for bigger teams.

SAFe incorporates knowledge from four different areas: Agile development, Lean product development, systems thinking, and DevOps. It blends Lean and Agile practices and applies them at an enterprise level to increase business agility and assist organizations as they grow in size. 

SAFe is divided into three segments: team, program, and portfolio. The framework offers guidance to organizations to work across these levels.:

- __Portfolio level:__ We’ll start with the portfolio level, which is the highest level of concern in SAFe and is the scope of responsibility of the organization’s management staff.<br> A portfolio is a number of value streams. Value streams budgeting and implementation is discussed at the portfolio level. A Backlog with Business Epics is generated at this level. Software testing and developing teams have nothing to do here so we won’t dwell on it a lot.

- __Team level__:
At the team level we deal with traditional agile teams and Scrum processes. There is a backlog with user stories. When planning a sprint, teams define work and efforts necessary to meet their sprint obligations. Once the two-week sprint is over, the team meets for Sprint Review, or Demo, and demonstrates some scope of functioning software that can be released. Daily meeting also take place.

- __Program level__:
The program level is where most of the SAFe differences from Scrum lie. First of all, the size of the development team is larger. The whole team is made up of the usual sprint teams that are applied to the ongoing development mission. The whole team in SAFe is called Team of Teams and can be composed of 50-125 specialists.<br>
The goal of the team is to deliver a Potentially Shippable Increment. “Potentially Shippable” is about the quality of the software, not its marketability. It should be free of defects and possess release quality. PSI is delivered during five sprints.

---
## __SAFe Agile Core Values__:
The SAFe Agile methodology is based on these four values:
- __Alignment:__ <br>SAFe supports alignment.<br>When companies are scaling Agile, all teams must be aligned across the organization and working towards the same goal. This is particularly vital for geographically dispersed teams where misalignment can hinder an organization’s ability to react to change. SAFe supports alignment by clearly outlining team roles and synchronizing activities, enabling organizations to keep up with competitors.

- __Built-in Quality__:<br>SAFe promotes a high standard of quality, ensuring that it remains a priority rather than an afterthought. It ensures that every incremental delivery reflects the quality standards.<br>Built-in quality is mandatory. Building these quality standards into the development life cycle is important, especially in a large-scale system where untested batches can pile up quickly.

- __Transparency:__<br>Transparency is crucial to building trust in teams and creating an open environment in an organization. Transparency is the enabler for trust. <br> SAFe helps the enterprise to achieve transparency at all levels- Executives, Portfolio Managers, and other stakeholders.<br> SAFe promotes transparency by ensuring full visibility into team backlogs, clearly outlining goals, and breaking workloads down into short-term commitments so obstacles can be spotted quickly.

- __Program Execution:__<br>Producing working software is a central tenet of SAFe and, indeed, Agile itself. SAFe places great focus on working systems and resultant business outcomes. Teams must be able to execute programs successfully to provide real business value. This is why SAFe places a huge emphasis on reliable systems that consistently deliver profitable outcomes.

SAFe is not useful if teams can’t execute and continuously deliver value.

---