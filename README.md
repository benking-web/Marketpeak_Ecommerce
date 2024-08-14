# Capstone Project. Introduction to Cloud Computing; E-commerce platform deployment with Git,Linux and AWS



# E-Commerce Website platform deployment for Marketpeak

## Name: Ugwu Emeka Ben-kingsley
position : Trainee Jnr DevOps Engr

see my picture below

![my_picture](images/![benking_pic](https://github.com/user-attachments/assets/2a6d86f2-2a4e-45fd-bcb8-936786237c67)





### Project Overview
This document outlines the process used to deploy the entire application flow. It includes steps from setting up the environment to deploying the website and troubleshooting issues. 



### Objectives

- The aim of the projectgoal is to set up a version control system using Git
- develop the website on a linux environment, and deploy it on an AWS EC2 instance.
- the static website of Maeketpeak_Ecommerce includes a home page, an about us page and a  contact page

  
### Setup: Git Version Control Sit-up

I already had Git, MobaXterm, and Visual Studio Code installed on my local machine. Here are the steps I followed to set up the project:

1. Git version control downloaded form google and installed.
2. Created new directory using the command: mkdir Marketpeak_Ecommerce
3. git initilization using this command : git init

   [(./images/
5. i prepared the E-commerce website template using a preexisting  e-commerce website template. i downloaded a free google template from using tooplate. extracted it the downloaded template into my my project folder called MarketPeak_Ecommerce via dare_iofolder. 
   []

   
   

6. Changed directory into the cloned folder (`greenwood-library-website`).
see attached screenshot of the cloned repository as well as the the commands on mobxterm terminal, which also shows the file path, git add, git commit and git push and collaboration between Morgan and Jamies.

[(./images/git_clone_file.png)]

[(./images/mobxterm_terminal_1.png)]
[(./images/mobxterm_terminal_2.png)]
[(./images/Mobxterm_terminal_3.png)]
[(./images/Mobxterm_terminal_4.png)]
5. On the main branch, created four HTML files inside Visual Studio Code:
   - `About_us.html`
   - `Contact_us.html`
   - `Home.html`

   [(./images/vscode_html_files.png)]

6. Added random contents to each of the files.
see the screenshot attached below:
[(./images/contact_us.html_file.png)]
[(./images/event.html_file.png)]
[(./images/home.html_file.png)]
[(./images/about_us.html_file.png)]


7. Staged the changes using:
   ```
   git add .
   ```
8. Checked the status of the repository:
   ```
   git status
   ```
9. Committed these changes to the project history:
   ```
   git commit -m "This is my first commit"
   ```
10. Pushed the main branch to GitHub:
    ```
    git push origin main
    ```
see pictures above on mobxterm terminal pictures
### Collaboration

#### Simulating Morgan's Work

1. Navigated to the cloned project directory (`greenwood-library-website`) and changed into it.
2. Created a new branch for Morgan's work:
   ```
   git checkout -b add-book-reviews
   ```
3. Created a new file named `book_reviews.html` using MobaXterm to represent the book reviews section.
4. Edited the file (`book_reviews.html`) using vi editor in MobaXterm, adding random text content.
5. Staged, committed, and pushed changes with a message:
   ```
   git add .
   git commit -m "Add book reviews section"
   git push origin add-book-reviews
   ```
6. Raised a pull request for Morgan's work and merged it into the main branch.

#### Simulating Jamie's Work

1. Updated the events page and created a branch named `update-events` from the main branch.
2. Staged, committed, and pushed changes with a message:
   ```
   git add .
   git commit -m "Update events"
   git push origin update-events
   ```
3. Raised a pull request for Jamie's changes and merged them into the main branch.

### Final Steps

Before raising a pull request for Jamie's update-events branch, I ensured to pull the latest changes into `update-events`.

see screen shot pictures above. thanks




