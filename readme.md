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
    
![image](https://github.com/user-attachments/assets/a3222e6d-d1c6-4246-a42a-590d49abe0ae)

Install Azure Static Web Apps Extension 

Open Visual Studio Code and open the file of the clone repository

<img width="327" alt="image" src="https://github.com/user-attachments/assets/38d8027a-a6d9-4765-85e8-a3a3acc25223">

Then:   Select View > Extensions.
In the Search Extensions in Marketplace, type Azure Static Web Apps.
Select Install for Azure Static Web Apps.

![image](https://github.com/user-attachments/assets/a7b647bb-8da8-4783-a3d9-9d82776efb42)

Create a Static Web App 

4.1 Open the Azure Extension Window

![image](https://github.com/user-attachments/assets/07bbceb6-ab4a-4dfb-bfc4-e945efdd56d7)

4.2 Select F1 to open the Visual Studio Code command palette.

![image](https://github.com/user-attachments/assets/5ca52a06-9733-45fa-8f55-358c053416df)

4.3 Enter Create static web app in the command box.

![image](https://github.com/user-attachments/assets/b07baf37-4c29-49a7-a33d-2bbc8380fc93)

4.4 Select Azure Static Web Apps: Create static web app....
4.5 Select your Azure subscription.
4.6 I entered my-first-static-web-app for the application name.

![image](https://github.com/user-attachments/assets/602579eb-d69b-4311-a725-a4bb1e911db8)

4.7 Select the region closest to you. In my case I used West US 2

![image](https://github.com/user-attachments/assets/2c28a6d3-f244-4d5b-9c4e-4690b02d22ce)

4.8 Enter the settings values that match your framework choice. In my case No framework

![image](https://github.com/user-attachments/assets/fc45def8-147b-4700-b307-1bdc93b8a248)
![image](https://github.com/user-attachments/assets/6a55874f-5028-4bd8-b791-42f179dd31d2)
![image](https://github.com/user-attachments/assets/1fb65f2c-0cbe-4a85-9582-407371d40486)

Then just press ‘Enter’, and the app will start to be created. 

Once the app is created, visual studio code will show a confirmation notification.   

![image](https://github.com/user-attachments/assets/06830412-9792-4519-8c84-67be20f9c79a)

To see the app on the web I did the following:  

<img width="342" alt="image" src="https://github.com/user-attachments/assets/f9ab0c09-632a-4239-8b4a-e31c99791b23">

From the Resources section:

Azure subscription 1 > Static Web Apps > my-first-static-web-app > Production

Then click on Production > Browse Site 

![image](https://github.com/user-attachments/assets/2613483c-956d-4f33-ae12-41364d63031d)

And it will direct you to the site of the app. 

<img width="330" alt="image" src="https://github.com/user-attachments/assets/2c177cfb-903e-4cd8-b301-9b0a2dc92dd0">

Looking at the URL, we can appreciate it ends with the Azure domain, which means The DNS record is in the Microsoft domain and provided by Microsoft.

Clean up resources

I’m not going to use this application, so I deleted the Azure Static Web Apps instance through the extension.

In the Visual Studio Code Azure window, return to the Resources section, and under Static Web Apps, right-click my-first-static-web-app and select Delete.

![Uploading image.png…]()

