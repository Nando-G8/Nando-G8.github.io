---
layout: default
title: Workforce Development Portfolio
---

# Creating a Personal GitHub Pages Site and E-Portfolio

## Introduction

GitHub Pages is a free and simple way to host a personal website directly from your GitHub repository. This is useful for creating a professional e-portfolio that showcases your background, skills, education, and work experience.

### In this guide, you will learn how to:

- create your personal GitHub Pages site
- set up the project files
- customize the theme
- replace the default branding with your own information
- build your portfolio page in index.md
- deploy the site and verify it is live

## Step 1: Create Your Personal GitHub Pages Repository

### 1.1 Sign in to GitHub

Go to GitHub and sign in to your account.

### 1.2 Create a new repository

Create a repository with this exact naming pattern:

your_github_username.github.io

### 1.3 Set the repository visibility

Choose the repository to be public or private. For GitHub Pages, public is the normal choice because the site must be viewable through the browser.

### 1.4 Create the repository

Once the repository is created, it will act as the home for your website.

## Step 2: Clone the Repository to Your Computer

### 2.1 Open your terminal or Git client

You can use GitHub Desktop or the VS Code terminal.

### 2.2 Clone the repository

Example:

bash
git clone https://github.com/your_folder/your_github_username.github.io.git

This creates a local folder on your computer where you can edit files and push changes back to GitHub.

## Step 3: Download the Minimal GitHub Pages Project

### 3.1 Download the project files
Minimal Theme Link: 
[https://github.com/pages-themes/minimal](https://github.com/pages-themes/minimal)

### Download the entire minimal project 

<img width="924" height="607" alt="image" src="https://github.com/user-attachments/assets/4c3b5948-c21a-4f2f-af86-eb99aeec761e" />


### 3.2 Unzip the files if necessary

If the project was downloaded as a zip file, extract it.

### 3.3 Place the downloaded project in your repository folder

Move the extracted project files into the local repository directory you cloned in Step 2.

Your repository should now contain the starter website files, including the main homepage file:

index.md
This is the file that will serve as the home page of your e-portfolio.

## Step 4: Commit and Push the Initial Project Files

### 4.1 Check the files in your repository

Open your repo folder and confirm that the project files are present.

### 4.2 Commit the changes
Run:

bash
git commit -m "Initial GitHub Pages setup"

### 4.3 Push to GitHub
Run:

bash
git push origin main
If your repository uses a different default branch name, replace main with the correct branch name.

### At this point, you have successfully set up the foundation for your GitHub Pages project.

## Step 5: Set Up the Theme Using the Project Instructions

### 5.1 Read the README file

Open the README.md file included in the project.

### 5.2 Follow the “Usage” section

The project README usually includes setup instructions for:

- theme selection
- site configuration
- optional customization settings

### 5.3 Follow the “Configuration variables” section

This section often explains how to edit configuration values such as:

- site title
- site description
- profile name
- theme options
- navigation settings

These settings are typically stored in a YAML configuration file such as:

_config.yml

### 5.4 Save and commit the configuration changes

After editing the configuration, commit and push your changes to GitHub.

## Step 6: Replace the Stock Image with Your Own Headshot

### 6.1 Locate the image file

In the project files, find the image folder. It is commonly inside something like:

Text
assets/img/
or:

Text
img/

### 6.2 Replace the default logo or profile photo

The project includes a stock image file, often named something like:

logo.png

Replace it with your own headshot using the same file name for convenience.

This makes the site easier to update without changing file references elsewhere.

### 6.3 Save the image

Make sure the file format is supported, such as .png or .jpg.

### 6.4 Commit the update

Save, commit, and push the change to GitHub.

## Step 7: Rewrite the Homepage Content in index.md

### 7.1 Open the homepage file

Navigate to the root file named:

index.md

This is the main page of your personal e-portfolio.

### 7.2 Replace the sample content

Delete the starter text and write your own information.

### A typical professional portfolio page can include:

1. a short summary or personal statement
2. work experience
3. education
3. projects
4. skills
5. contact information

- GitHub: [github.com/yourusername](https://github.com/yourusername)
- Email: yourname@example.com

### 7.3 Include personal and professional content

Add information relevant to your academic and professional background

## Step 8: Final Commit and Push

Once you have double checked everything and it is to your satisfaction, commit changes and push 

## Step 9: Check GitHub Pages Deployment

### 9.1 Open your repository on GitHub

Go to:
https://github.com/<your_github_username>/<your_github_username>.github.io

Check whether the GitHub Pages deployment is running successfully.


### 9.2 Confirm that deployment succeeded

If the build finishes successfully, GitHub Pages will publish your site.

## Step 10: View Your Live Portfolio Website

After deployment completes, visit your website in a browser:

https://<your_github_username>.github.io

### If the page loads and shows your updated content, the site has been successfully deployed.

### Here is a screenshot of my complete e-portfolio

assets/img/e-portfolio_screenshot.png

