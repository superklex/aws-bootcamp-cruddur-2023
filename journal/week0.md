# Week 0 — Billing and Architecture


## Introduction

The program officially kicked off on the 11th of February 2023 with a [youtube video](https://www.youtube.com/watch?v=SG8blanhAOg&list=PLBfufR7vyJJ7k25byhRXJldB5AiwgNnWv&index=12) where an overview of the proposed Cruddur microblogging app was laid down.

Following the official kickoff, a number of tasks were given to be completed before the next session. Below is my checklist and execution of said tasks


## Required Homework


### 1. Week0 Spend Consideration

I watched and understood [Chirag's week0 spend considerations video](https://www.youtube.com/watch?v=OVw3RrlP-sI&list=PLBfufR7vyJJ7k25byhRXJldB5AiwgNnWv&index=14) which gave insights into AWS billing console and how to set up budgets and alarms as a means to safeguard against overspending.


### 2. Week0 Security Consideration

I watched and understood [Ashish's week0 security considerations video](youtube.com/watch?v=OVw3RrlP-sI&list=PLBfufR7vyJJ7k25byhRXJldB5AiwgNnWv&index=15)which highlighted security practises such as setting up IAM users and roles importance of enabling MFA, using cloudtrail and a number of other security practises.

This was quite important to know because, while AWS is responsible for the security of the cloud, I am responsible for the security **of** my infrastructure **in** the cloud


### 3. Recreate Conceptual Diagram on a Napkin

I created a conceptual diagram of the Cruddur microblogging application on a [napkin saved on my Github](https://github.com/superklex/aws-bootcamp-cruddur-2023/blob/week0/journal/myAssets/week0/myCruddurNapkinConceptualDiagram.jpeg)
![image of napkin conceptual diagram](/journal/myAssets/week0/myCruddurNapkinConceptualDiagram.jpeg)


### 4. Recreate Logical Architectural Diagram in Lucid Charts

Following [Andrew Browns Lucid Chart walkthrough video](https://www.youtube.com/watch?v=K6FDrI_tz0k&list=PLBfufR7vyJJ7k25byhRXJldB5AiwgNnWv&index=17) I created a logical Architectural diagram of the Cruddur microblogging application in [my Lucid Charts account](https://lucid.app/lucidchart/8433e01a-0ee4-4ffb-be2f-ae881a524bc7/edit?invitationId=inv_da696cf9-dc84-4b71-8b7c-88afdb1979c5) which I uploaded to [my github](https://github.com/superklex/aws-bootcamp-cruddur-2023/blob/week0/journal/myAssets/week0/myCruddurLucidLogicalDiagram.jpeg)
![image of logical architectural diagram](/journal/myAssets/week0/myCruddurLucidLogicalDiagram.jpeg)


### 5. Create an Admin User

Prior to the kickoff of the program, while going through one of the [prerequisite courses](https://www.youtube.com/watch?v=SOTamWNgDKc), I created a new AWS account and an Admin user


### 6. Use Cloud Shell

Folowing [Andrew Brown's afterclass stream](https://www.youtube.com/watch?v=OdUnNuKylHg&list=PLBfufR7vyJJ7k25byhRXJldB5AiwgNnWv&index=14), I was able to run the ```aws sts get-caller-identity''' command on the AWS cloudshell
![AWS Cloudshell image](/journal/myAssets/week0/cloudshell.png)


### 7. Install AWS CLI

Still Following  [Andrew Brown's after-class stream](https://www.youtube.com/watch?v=OdUnNuKylHg&list=PLBfufR7vyJJ7k25byhRXJldB5AiwgNnWv&index=14) as well as instructions from the [official AWS CLI installation guide](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html#getting-started-install-instructions), I was able to get my AWS CLI working hitch-free


### 8. Create a Billing Alarm
I was able to successfully create a billing alarm using the AWS CLI while following along with [Andrew Brown's video walkthrough](https://www.youtube.com/watch?v=OdUnNuKylHg&list=PLBfufR7vyJJ7k25byhRXJldB5AiwgNnWv&index=14)
![Billing alarm image](/journal/myAssets/week0/billing%20alarm.png)

### 9. Create a Budget
I successfully created a budget on my AWS account following the steps outlined by Andrew Brown in [his after-class video](https://youtu.be/OdUnNuKylHg?list=PLBfufR7vyJJ7k25byhRXJldB5AiwgNnWv&t=3868) using the CLI.
![image of budgets](/journal/myAssets/week0/budgets.png)



## Summary
Week0 was a good and relatively easy week. It laid the groundwork for the future days of this project which might become tougher as the weeks go by.

That being said, I refuse to give up or get discouraged because I know that character and proper experience are developed by overcoming challenges and tough times.

I wil end with the quote by *Charlie Norman*:
> it's easy on the good days, but it's really earned on the tough days. Your life and your goals don't care how you feel.


