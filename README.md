### tour-of-playwright-heros

### 
 - clone the repo
 - npm install
 - npm run start
 - npm run e2e

# Getting started with the Playwright framework
Playwright is a platform which we can use to help us with end-to-end testing. It supports all modern rendering engines including Chromium, WebKit, and Firefox.

### Some of the basic prerequisites that are needed for installation and setup.
###
  - Ensure you have NodeJS installed.
  - Install a code editor. We will be using Visual Studio Code.

#### Creating your first Playwright project
 There are a few different ways we can install Playwright.
   1. Follow the below steps to install Playwright using the VS Code extension:
       - Create a folder for your project
       - Ensure to open this folder in vs code
       - Install `Playwright Test for VSode` Extension
         
         <img width="395" alt="image" src="https://github.com/mkothur/tour-of-playwright-heros/assets/53789187/84960704-1f4b-42d6-8a04-bd709ed2d9f2">

       - open the ‘Command palette’ under the ‘View’ tab, and type ‘install Playwright.’ Ensure you have created a folder for your project, which is currently open in VS Code, as this is where the new Playwright files will be generated.
         <img width="383" alt="image" src="https://github.com/mkothur/tour-of-playwright-heros/assets/53789187/0778c491-1140-4bdc-8171-ff33b5a18492">
       - After selecting this, you’ll be presented with the following dropdown options, where you can choose which browsers to install. You can also add GitHub Actions, which will generate a YAML build file for you.
         <img width="602" alt="image" src="https://github.com/mkothur/tour-of-playwright-heros/assets/53789187/a61f25ff-7d23-4c2c-9856-5f20a4698534">
       - When this is successfully installed, you should see the following message in the command line, which presents you with a few commands you can execute to get started:
         
         <img width="496" alt="image" src="https://github.com/mkothur/tour-of-playwright-heros/assets/53789187/8baa5e53-e1ae-4bf3-b2f6-1db343340645">

       - project created that looks like this
    
         <img width="212" alt="image" src="https://github.com/mkothur/tour-of-playwright-heros/assets/53789187/a45e5f98-4572-4af5-b6a2-878abb71d2da">

       - Run this command `npx playwright test` to execute the sample test specs.
       - Run this command `npx playwright show-report` to view report in UI.

  2. Installing the Playwright NPM package from the command line
      - npm init playwright@latest new-project
      - Choose the options from the terminal prompts which outline to configure the project
      - After following these steps, you’ll have a similar project structure as the VS Code extension workflow. The only difference is that the command line installation offers slightly more customization in choosing between JavaScript and TypeScript, and test folder location.
    
 ##### playwright.config.js: This is where you can add configuration for Playwright, including modifying which browsers you would like to run Playwright on.
     
  


         



  
