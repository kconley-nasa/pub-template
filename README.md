------------------------------------------------------

# A README template mandatory for inner-source repos and optional for everyone else

### Instructions for how to use:

1. On your personal developer.nasa.gov/<username> page or the initial developer.nasa.gov page, click the big green button that says "NEW". This will start a new repository.
  
2. You'll see an option at top of the page that appears now that says "Repository Template", click the button below that says "no template" and select from the drop down <b>meta/README_template</b>. 

3. When you start your new repository, it willl initially populate with this README. Click the edit button in upper left when you see your repository for the first time. This will start to edit the README.md markdown file. 

4. Delete these instructions and makes changes as appropriate for your project!

NOTE: If you're using this as a guide to modify an existing repository, it is easier to fork, select edit, and then copy and paste out the text in markdown form into your existing markdown.

<i>The upper sections of this README are mandatory for official software reuse according to NPR 7150.2C and the NASA Software Engineering Handbook. The lower sections are good information to include for almost any repository. </i>

------------------------------------------------------

# Title of the Repository
<i>The name of the repository & softare project.</i>

## Description
<i> Please include a description of the software project. This should be 1-10 sentences and give someone who has no knowledge of your project a good idea of what it does and why you think it has value and should exist.</i>


### The Civil Servant Software Technical Point of Contact for the software product. 
<i>It is required to include the name and email of the civil servant who is the technical point of contact for the software project. This person may be writing code or the project owner. </i>

## Language(s) used by the software
<i>Example might be "Python, JavaScript, HTML, CSS". If possible keep on one line, separate with commas, and put in order of amount of code. Theoretically in the future this information might be extracted in bulk across all similar READMEs.</i>


## License information for any code dependencies
<!--
The actual language from NPR 7150.2C is "Any third party code contained therein, and the record of the requisite license or permission received from the third party permitting the Government’s use, if applicable."
-->
<!-- 
There are a different ways to fulfull this. The most straight forward way is to (1) confirm each of your dependencies has a license that allows you to use it (2) make a requirements.txt file or another file type depending on the code language that shows all your dependencies. 
EXAMPLE: 
-->
Confirming the proper licenses exist is a requirement both to share and use any code.

You can find all the dependencies for this repository this repository's file for dependency management. This may be a requirements.txt file if Python or package.json if JavaScript. If this type of file doesn't exist, any dependencies will be listed in this README.md file. The authors of this repository have confirmed each has an open-source licenses suitable for government use. You should confirm this as well by either looking in the files for that dependency or looking up the dependency in the appropriate package directory.

## Warning Label
<!--
### Your README should contain the phrase below. It comes from NPR 1750.002C under the section for software reuse and as such is NASA policy. 
-->
<b><i>"This software may be subject to U.S. export control restrictions, and it is provided "as is" without any warranty, express, or implied and that the recipient waives any claims against, and indemnifies and holds harmless,
NASA and its contractors and subcontractors "</i></b>
.

**By accessing and using this information system, you acknowledge and consent to the following:**

> You are accessing a U.S. Government information system, which includes:
> 
> 1. this computer;
> 1. this computer network;
> 1. all computers connected to this network including end user systems;
> 1. all devices and storage media attached to this network or to any computer on this network; and
> 1. cloud and remote information services.
> 
> **This information system is provided for U.S. Government-authorized use only.**

> You have no reasonable expectation of privacy regarding any communication transmitted through or data stored on this information system. At any time, and for any lawful purpose, the U.S. Government may monitor, intercept, search, and seize any communication or data transiting, stored on, or traveling to or from this information system.
> 
> You are **not** authorized to process classified information on this information system. Unauthorized or improper use of this system may result in suspension or loss of access privileges, disciplinary action, and civil and/or criminal penalties.

<b><i>"<a href="https://developer.nasa.gov/jgossess/banner/blob/master/README.md">Please note by using developer.nasa.gov to access this code repository you are aknowledging and consenting to the following statements on the developer.nasa.gov warning banner page that apply to any code repository stored on developer.nasa.gov.</a>"</i></b>

<b>This software is for internal use only and has not been approved for public release.</b>



####
------------------------------------------------------


<i>--------- Sections ABOVE ARE MANDATED BY NASA POLICY FOR SOFTWARE REUSE ---------</i>


<i>--------- Sections BELOW ARE HEAVILY ENCOURAGED BUT NOT MANDATED BY NASA POLICY ---------</i>

#### 
------------------------------------------------------



## Requests if used by people who are not the author
<!-- example text-->
If you find this repository useful, even a little, please fork or star thee repository! It provides positive feedback to the developer as well as helpful analytics data to the platform maintainers. If whether you can reuse code is in any way unclear, please reach out to code repository author / point of contact.

## Organization of code contributors & project owners
<i>Please put an organization name here that is meaningful. Often organization at certain centers are known by your code. The problem with just listing that by itself is it is often meaningless to anyone not at your center. If the code project involves work by more than one team or there was a main team and then others joined, pleaes describe that here.</i>

## Contractor Author Point of Content
<i>If the author(s) of the code are contractors, it may be appropriate to list their names and/or email in addition to the civil servant point of contact</i>

## Installation Instructions
<i>Please include instructions for how a newbie to your project could install it.</i>

## How to Use
<i>Please include instructions for how a newbie to your project could use it. This might be a demo, tutorial, or simply list of instructions.</i>

## State of Project

Please describe the state of the project. Examples are: 

This code repository is - 
- a quick evaluation of an external open-source project,
- a guide
- a reusable script, 
- a proof-of-concept, 
- a working prototype, 
- a code project used in production

## Who Would Benefit From This Project
<i>Please state who you think would benefit and how they might use it.</i>

## Contributing
Some possible contributing statements:

This project is -
- This project is not under activate development and the original author has left NASA.
- This project is not under activate development and not taking contributions.
- This project is not under activate development but please submit an issue or email if you see a problem or have a question.
- This project is open to collaborations or requires for more information. 
- This project is stable, please feel free to reuse.
- This project is being used in production situations, please reach out to us about reuse.
- This prooject is under activate development and rapidly changing, please reach out before using.
- This prooject is under activate development and rapidly changing, please be careful.
- This project actively engages with potential users and collaborators. Please please tell us how you're thinking of using this repository. 
- See our Contributing.md file for how to contribute.


## Other Information
- <i>This repository was created from a template available <a href="https://developer.nasa.gov/meta/README_template">here</a>.
- You can find other repository resources in the <a href="https://developer.nasa.gov/meta/repository-resources/blob/master/README.md">meta/repository-resources/</a> repository.
- Different software classification have different NASA requirements. Nearly all of the code repositories with the inner-source topic tag on developer.nasa.gov as of 2020-10-12 are class E for example. You can see the definitions for the various classifications of software in <a href="https://swehb.nasa.gov/display/7150/7.2+-+Classification+Tool+and+Safety-Critical+Assessment+Tool">Software Engineering Handbook classification tool</a> and <a href="https://swehb.nasa.gov/display/7150/7.2+-+Classification+Tool+and+Safety-Critical+Assessment+Tool">flowchart</a>.
