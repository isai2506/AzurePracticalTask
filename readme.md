# Vanilla JavaScript App

[Azure Static Web Apps](https://docs.microsoft.com/azure/static-web-apps/overview) allows you to easily build JavaScript apps in minutes. Use this repo with the [quickstart](https://docs.microsoft.com/azure/static-web-apps/getting-started?tabs=vanilla-javascript) to build and customize a new static site.

This repo is used as a starter for a _very basic_ HTML web application using no front-end frameworks.

This repo has a dev container. This means if you open it inside a [GitHub Codespace](https://github.com/features/codespaces), or using [VS Code with the remote containers extension](https://code.visualstudio.com/docs/remote/containers), it will be opened inside a container with all the dependencies already installed.

![image](https://github.com/user-attachments/assets/50bdd975-0981-4ca2-aec6-95615f0a59a4)



Azure Practical Task


For this task, I did my first static site with the help of Quickstart: Build your first static site with Azure Static Web Apps, provided by Microsoft. 

Prerequisites:  GitHub account
Azure account
Visual Studio Code
Install Git

Create a GitHub repository
 
I used the following link: https://github.com/login?return_to=/staticwebdev/vanilla-basic/generate to create a repository and I named it my-first-static-web-app. 

In my case I used no framework. 

Clone the repository 

I used the git clone command in the terminal to be able to use the repository on my local machine. 

		git clone https://github.com/isai256/my-first-static-web-app.git
    
![Uploading image.png…]()





Install Azure Static Web Apps Extension 

Open Visual Studio Code and open the file of the clone repository

Then:   Select View > Extensions.
In the Search Extensions in Marketplace, type Azure Static Web Apps.
Select Install for Azure Static Web Apps.


















Create a Static Web App 

4.1 Open the Azure Extension Window









4.2 Select F1 to open the Visual Studio Code command palette.


















4.3 Enter Create static web app in the command box.



4.4 Select Azure Static Web Apps: Create static web app....
4.5 Select your Azure subscription.
4.6 I entered my-first-static-web-app for the application name.
4.7 Select the region closest to you. In my case I used West US 2


4.8 Enter the settings values that match your framework choice. In my case No framework



Then just press ‘Enter’, and the app will start to be created. 

Once the app is created, visual studio code will show a confirmation notification.   









To see the app on the web I did the following:  



























From the Resources section:

Azure subscription 1 > Static Web Apps > my-first-static-web-app > Production

Then click on Production > Browse Site 



















And it will direct you to the site of the app. 



Looking at the URL, we can appreciate it ends with the Azure domain, which means The DNS record is in the Microsoft domain and provided by Microsoft.



Clean up resources

I’m not going to use this application, so I deleted the Azure Static Web Apps instance through the extension.

In the Visual Studio Code Azure window, return to the Resources section, and under Static Web Apps, right-click my-first-static-web-app and select Delete.

