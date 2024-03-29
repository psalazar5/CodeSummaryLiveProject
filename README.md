# CodeSummaryLiveProject

## Introduction
During the last two weeks at the tech academy, I collaborated with my team to develop a full-scale MVC Web Application in C#. Utilizing Azure DevOps with my scrum master, we successfully implemented a code-first Entity Framework database and created CRUD functionality pages for different sections of the website, enabling efficient information management.

Despite encountering significant changes that could have caused delays, we remained agile and delivered the required features on time. This experience taught me the importance of resourcefulness and how to work efficiently to produce a high-quality product.

Throughout the project, I took great pride in focusing on several [backend stories](#back-end-stories). Additionally, given that the site was already in its middle of the life cycle, I actively contributed to various [frontend stories](#front-end-stories), each with its own level of complexity.

Each team member had the opportunity to work on both frontend and backend tasks, ensuring a well-rounded learning experience. We also regularly utilized version control, performing tasks such as updating the master branch, pulling changes from Azure to the local machine, creating new branches, and submitting pull requests.

Below are descriptions of the stories I worked on, along with code snippets and navigation links. I also have some full code files in this repo for the larger functionalities I implemented.


# Back End Stories
* [Code First Entity Framework Database](#code-first-entity-framework-database)
* [Scaffolding CRUD Pages](#scaffolding-crud-pages)

# Front End Stories 
* [CSS MVC Editing](#css-mvc-editing)
* [Create And Edit CRUD Pages](#create-and-edit-crud-pages)
* [Edit and styling Index of RentalHistory](#edit-and-styling-index-of-rentalhistory)

 Jump to: [Page Top](#codesummaryliveproject), [Back End Stories](#back-end-stories), [Front End Stories](#back-end-stories)

# Code First Entity Framework Database
In this part of WIP project I had to create a model for a Rental History page including CRUD functionality. There were two parts to this story, first creating an entity model for the RentalHistory class so it can be saved into the database, then scaffolding CRUD pages for it and using SQL Server to check if the table had been created accordingly. 

<h3>Database in SQL: </h2>
<img src="https://github.com/psalazar5/CodeSummaryLiveProject/assets/96414596/3a6b4d47-a448-4c60-aed4-d1b42f7f40c5" width = "700 " height = "500"> 
<h3>The Entity Model:</h2>
<img src="https://github.com/psalazar5/CodeSummaryLiveProject/assets/96414596/420e5afd-c7a8-4d86-9fea-4a2bb9eb4eaa" width = "700" height = "500">

### Scaffolding CRUD Pages 
This is the second part where I scaffolded the CRUD pages for it's functionality and it's final result: 

<h3>Made sure to add layout: </h3>
<img src = "https://github.com/psalazar5/CodeSummaryLiveProject/assets/96414596/9be41301-8fc5-4b5d-b07a-823ebcc7f9ba" width="400" height="300">

<h3>Scaffolding CRUD:</h3>
<img src = "https://github.com/psalazar5/CodeSummaryLiveProject/assets/96414596/fc2e7d90-c7d0-440c-b9c0-13bda915c31e" width="700" height="500"> 

<h3>CRUD Pages:</h3>
<img src = "https://github.com/psalazar5/CodeSummaryLiveProject/assets/96414596/824bd8a7-5664-42a4-93b3-ea7039f1a030" width="" height="">

<h3>Final Creation:</h3>
<img src = "https://github.com/psalazar5/CodeSummaryLiveProject/assets/96414596/f35a6b49-bc34-4d8c-83b8-34ab0f2cca6a" width="700" height="500"> 

<h3>Git Changes in the end: </h3>

<img src = "https://github.com/psalazar5/CodeSummaryLiveProject/assets/96414596/efaef9d1-62c8-437a-95d5-a9f1fdfedc6d" width="220" height="350"> 

 Jump to: [Page Top](#codesummaryliveproject), [Back End Stories](#back-end-stories), [Front End Stories](#back-end-stories)

# CSS MVC Editing:
In the front end of this WIP project I needed to change the Donate View in the Home View Folder in order to stylize the fields where the end user enters their information and donation amount. In order to make this possible I utilized bootstraps grid layout to create the layout of the page. My scrum master 
implied that there needed to be an imaged displayed behind the title as well, and the font of the title should be Broadway. I added placeholders to every field so a user can fill in.

<h3>DonationViewHTML:</h3>
<img src = "https://github.com/psalazar5/CodeSummaryLiveProject/assets/96414596/b2965490-aa0b-4bb4-b71d-c0f940289581" width="700" height="450">

<h3>DonationViewCSS:</h3>
<img src = "https://github.com/psalazar5/CodeSummaryLiveProject/assets/96414596/151f7572-6416-45aa-8329-868fa02e71f3" width="700" height="450">

<h3>Donation View in Home View Folder: </h3>
<img src="https://github.com/psalazar5/CodeSummaryLiveProject/assets/96414596/52acdc95-4a06-4bac-bcf8-e600756e0498" width="130" height="150">

<h3>Product: </h3>
<img src="https://github.com/psalazar5/CodeSummaryLiveProject/assets/96414596/8f75bf7a-1deb-4d19-af05-77d5516aea5d" width="1000" height="480">

## Create and Edit CRUD Pages: 
In this third part of my story I was advised to create and edit RentalHistory labels, bringing back the 'Back to List' button and 'Create' button into the form centering it. Lastly, if a rental is not damaged, the 'DamagesIncurred property should represent 'notes' as is and if 
damaged box is checked then 'Notes' should be customized to 'DamagesIncurred'. For this part I utilized Jquery to make this possible. 

<h3>Styling Page Product: </h3>
<img src="https://github.com/psalazar5/CodeSummaryLiveProject/assets/96414596/a50287d6-57d7-4604-bc1c-6064c004eda6" width="" height="">

<h3>Visual Studio Multi-tasking Work:</h3>
<img src="https://github.com/psalazar5/CodeSummaryLiveProject/assets/96414596/a9e2c0b1-1be3-45c8-8bc4-8a42a3fa5f5c" width="1000" height="500">

<h3>Create.cshtml:</h3>
<img src="https://github.com/psalazar5/CodeSummaryLiveProject/assets/96414596/9f1c1b24-62cb-49ef-b177-ae3ab79519ba" width="1000" height="600">

<h3>Rent.css:</h3>
<img src="https://github.com/psalazar5/CodeSummaryLiveProject/assets/96414596/2fdfc625-b567-4f13-a88e-374f893d3772" width="500" height="800">

 Jump to: [Page Top](#codesummaryliveproject), [Back End Stories](#back-end-stories), [Front End Stories](#back-end-stories)

<h3>CRUD Page and Jquery:</h3>

https://github.com/psalazar5/CodeSummaryLiveProject/assets/96414596/bf6aa6f7-daef-4185-9833-6844d710b043

# Edit and styling Index of RentalHistory
In the last parts of my project I was instructed to display a RentalHistory Index page where all histories are displayed to the end user into a tabular form. In order to do this within a table I utilized html, css, bootstrap, razor syntax, etc. 
I stylized the page where if the RentalDamaged box was checked from the last assignment, then there should be a red X checkmark on the left side of the cell. If the RentalDamaged box was not checked then there should be a green checkmark. 
After the X or checkmark symbol, the name of the Rental should be displayed. I stylized the name so that it's distinguished from the other text in the cell with bootstrap utilization. After the Rental name, I displayed the damages incurred text. If the Rental was not damaged, I greyed out this text slightly. The damages incurred text shouldn't wrap to a new line. If the length of the damages incurred text would wrap or go out of the cell, I used ellipses ( . . . ) to cut off the text. When hovering over a cell, vertical ellipses should appear.  This is a dropdown containing the Edit, Details, Delete buttons

<h3> Before and After: </h3>
<img src = "https://github.com/psalazar5/CodeSummaryLiveProject/assets/96414596/2e90329d-ffd7-4a23-a78f-fb79f177424b" width = "1000" height = "300">

<img src = "https://github.com/psalazar5/CodeSummaryLiveProject/assets/96414596/48b5d2b3-afeb-4ace-95ed-13848225a6f8" width="1000" height="300">

<h3>Full Page:</h3>
<img src= "https://github.com/psalazar5/CodeSummaryLiveProject/assets/96414596/07133aa0-7e68-4025-b34e-a8bcee830204" width = "1000" height = "800">


<h3>Index.css:</h3>
<img src = "https://github.com/psalazar5/CodeSummaryLiveProject/assets/96414596/7fb8fcc2-cc51-478c-b05a-4259c30f014f" width = "300" height = "700">


<h3>Index.cshtml Razor Table, looping: </h3>
<img src = "https://github.com/psalazar5/CodeSummaryLiveProject/assets/96414596/6d7d4b86-efc9-4361-bd00-268bbc94ef85" width = "1000" height = "600">

 Jump to: [Page Top](#codesummaryliveproject), [Back End Stories](#back-end-stories), [Front End Stories](#back-end-stories)

 

# Summary 
During the final two weeks of the bootcamp's live project, I effectively applied my expertise in ASP.NET MVC, HTML, CSS, jQuery, Bootstrap, and various other technologies. Working with my scrum team proved to be an intriguing experience, requiring me to navigate challenges independently when faced with difficult situations.

Utilizing Azure DevOps and embracing scrum methodologies for the first time significantly improved my understanding of application development, enhanced communication with my team and scrum master, and honed my resource management skills. Moreover, this experience encouraged me to seek clarification on unfamiliar topics and provided ample opportunities for future brainstorming.

Engaging with the scrum team during project development allowed me to gain a more comprehensive perspective on the tasks at hand, enabling better communication with the scrum master and fostering a transparent and proactive approach to problem-solving. This involvement instilled the importance of regular stand-ups and code retrospectives, promoting continuous learning and improvement.

I intend to carry forward these valuable methodologies from my live project to my future software development career. By maintaining consistent and effective communication, setting appropriate boundaries as a newcomer in the industry, and cultivating a growth mindset, I aim to avoid stagnation. Additionally, I plan to apply the principles of algorithmic thinking to tackle interview questions, approach technical challenges, and overcome obstacles with efficiency.
