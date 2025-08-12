
## Practice Project - Scenario & Overview

**Estimated Time:** 15 minutes

#### Scenario

You have recently joined a logistics company seeking to enhance its supply chain management process by creating a shipping calculator web application. The company's objective is to establish a robust, efficient, and transparent system for calculating shipping costs and providing delivery estimates to its customers.

In today's dynamic business environment, collaboration and knowledge sharing are crucial in advancing research and fostering growth.

Within this company, multiple teams are concurrently working on different products. Therefore, it is imperative to ensure seamless collaboration, effective version control, and efficient project management. The company has decided to use GitHub as its web-based interface.

Your assignment involves harnessing GitHub's collaborative and version control features to oversee the development and deployment of the shipping calculator web application. This initiative aims to lead to an optimized supply chain management process.

  

#### Overview:

This practice project consists of two parts.

#### Part 1: Using GitHub UI

You are asked to host the starter code of your company to calculate shipping logistics rates on GitHub in a new repository as the first step. You will not only host the script but also follow the best practices introduced in this course and create supporting documents for the open source project, including a code of conduct and contributing guidelines. Additionally, the repository should be available to the community under the Apache License 2.0.

This will be done on the GitHub UI.

#### Part 2: Using GitHub CLI

You have successfully started your company's journey with GitHub by creating a repository for the Shipping Calculator application. All the developers have contributed, and their changes have been accepted and merged into a new global repository: [https://github.com/ibm-developer-skills-network/Centralized-repository-shipping_calculations.git](https://github.com/ibm-developer-skills-network/Centralized-repository-shipping_calculations.git). Now, you have been asked to edit some of the codes and also add few more files. For this, you will fork this global repository, make the necessary edits, and add files using Git CLI in the provided lab environment. Finally, you will open a pull request to contribute your changes to the global repository.

This will be done on the CLI.
% buffered00:00

00:00

# Practice Project: Part 1 - GitHub UI

**Estimated Time:** 30 minutes

## Overview

In this lab you will start your journey with the GitHub implemention for your organisation by creating a repository in your GitHub account and then initialising the repository with a README.md file and a License. Following this, you'll update the README file to include a Code of Conduct and Contribution Guidelines markdown files. After making these changes, you'll commit the files to your repository.

Next, you'll create a new branch and add code for Shipping logistics calculation. To wrap up, you'll merge this branch into the main branch using a Pull Request.

## Objectives

After completing this lab, you will have demonstrated that you can:

1.  Create a repository with a README.md file and a license.
2.  Update the existing files.
3.  Commit the files to your repository.
4.  Create a new branch and add files to it.
5.  Merge this branch to the main branch using a Pull Request.

## Task 1: Create a repository with a README file and a license.

1.  At the top right of the GitHub home page, click on the `+` icon and select `New repository`.

![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0131EN-SkillsNetwork/labs/Practice_Project/images/new-repo.png)  
  

2.  Create a new GitHub repository called `LogisticsShippingRates` and make sure that it is **Public**.
    
3.  Select the **Add a README file** field. Click on the **Choose a license** field and select `Apache License 2.0` from the drop down. Finally, click on **Create repository**.
    

![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0131EN-SkillsNetwork/labs/Practice_Project/images/create-new-repo.png)  
  

4.  After successfully creating a new repo, you will see the following screenshot.

![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0131EN-SkillsNetwork/labs/Practice_Project/images/success-new-repo.png)  
  

Your repository is created and includes the README and LICENSE files. Now, you are ready to update your repository files to include useful information for your community.  
  

## Task 2: Update the README file.

1.  Click on `README.md` file to open it and click the pencil icon to edit it.

![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0131EN-SkillsNetwork/labs/Practice_Project/images/edit-readme.png)  
  

2.  Add the following information to the file:



1.  `Please consider the below factors while contributing`

3.  `Code  Style:`
4.  `Maintain a consistent code style for readability.`

6.  `Documentation:`
7.  `Ensure well-documented code for effective collaboration.`

9.  `Testing:`
10.  `Thoroughly test your changes before submitting a pull request.`

12.  `Issue  Tracker:`
13.  `Check the Issue  Tracker  for tasks.`

15.  `Code  Review:`
16.  `All contributions undergo a code review process.`

18.  `Licensing:`
19.  `Contributions are licensed.`

          

3.  Now click on `Commit changes`

![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0131EN-SkillsNetwork/labs/Practice_Project/images/commit-readme.png)  
  

4.  Ensure that the radio button to **commit directly to the main/master branch** is selected. Add a commit message and click on `Commit Changes`

![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0131EN-SkillsNetwork/labs/Practice_Project/images/commit-readme-to-MASTER.png)  
  

> **NOTE**: After completing the steps in each of the tasks, if you are unable to see the options depicted in the provided screenshots, click on the `Code` option as highlighted in below screenshot:

> ![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0131EN-SkillsNetwork/labs/Practice_Project/images/NOTE-main-repo.png)  
>   

## Task 3: Add a code of conduct.

A code of conduct helps set ground rules for the behavior of your project's participants. It defines standards for how to engage in a community.

GitHub provides templates for common codes of conduct to help you quickly add one to your project.

1.  To create a new file click on **Add file** and then `Create New File`.

![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0131EN-SkillsNetwork/labs/Practice_Project/images/create-file.png)  
  

2.  Add a new file named `CODE_OF_CONDUCT.md` to the root folder of the repository. The **Choose a code of conduct template** button is displayed.

![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0131EN-SkillsNetwork/labs/Practice_Project/images/code-of-conduct.png)  
  

3.  Click the **Choose a code of conduct template** button. You will see a popup mentioning you may lose unsaved changes. Click on `OK`.

![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0131EN-SkillsNetwork/labs/Practice_Project/images/POPUP_code-of-conduct.png)  
  

4.  Click on `Contributor Covenant` to load this template. Then click `Review and submit` to add the file to your project.

![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0131EN-SkillsNetwork/labs/Practice_Project/images/contributor-covenant.png)  
  

5.  Scroll down the page to read the content. Click on `Commit changes`.

![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0131EN-SkillsNetwork/labs/Practice_Project/images/scroll+commit_code-of-conduct.png)  
  

6.  Ensure that the radio button to **Commit directly to the main/master branch** is selected and click `Commit changes`.

> **NOTE:** In the past the default branch in your GitHub repo used the name `master`. Effective Oct 1. 2020, all new GitHub repositories use the more inclusive term `main` as the name of the default branch instead of `master`.

![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0131EN-SkillsNetwork/labs/Practice_Project/images/commit-code-of-conduct.png)  
  

> If the page is zoomed in, you may see only the **Commit changes** button and not the radio button. Zoom out or scroll down to see the radio button.  
>   

7.  Your project now contains a code of conduct.  
    ![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0131EN-SkillsNetwork/labs/Practice_Project/images/success-code-of-conduct.png)  
      
    

## Task 4: Establish contribution guidelines.

Contribution guidelines provide clear instructions for individuals looking to contribute to the project. To implement these guidelines, please follow these steps:

1.  Create a new file in the repository's root directory and name it `CONTRIBUTING.md`.
    
2.  Inside the file, include the following information:
    


1.  `Contribution guidelines`
2.  `Welcome  Contributors!`
3.  `Thank you for considering contributing to the centralized repository.  This document outlines the guidelines for contributing to the development of Shipping  Rates  and  Calculations.`

5.  `Code style`
6.  `Please follow the coding style and conventions used in the existing codebase.  This helps maintain consistency across the project.`

8.  `Documentation`
9.  `Ensure that your contributions are well-documented.  Include comments in your code where necessary and provide a clear and concise description of your changes in the pull request.`

11.  `Testing`
12.  `Before submitting a pull request, make sure your changes have been tested thoroughly.  Include relevant test cases and  ensure that existing tests pass.`

14.  `Issue tracker`
15.  `Check the issue tracker for any open issues or feature requests.  If you're working on something, please comment on the issue to let others know.`

17.  `Code review`
18.  `All contributions will go through a code review process. Be open to feedback and be willing to make changes if necessary. Code reviews help maintain code quality and consistency.`

20.  `Thank you for your contribution!`

          

3.  Commit this file to your repository.

![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0131EN-SkillsNetwork/labs/Practice_Project/images/commit-CONTRIBUTING.png)  
  

4.  Click on `Code` to go to the repository home page.

![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0131EN-SkillsNetwork/labs/Practice_Project/images/code_homepage.png)

Your project now contains Contribution Guidelines as well.

## Task 5: Create a new branch.

1.  Click on `branch` in your repository.

![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0131EN-SkillsNetwork/labs/Practice_Project/images/create-branch.png)

2.  Now, click on `New Branch` and enter the branch name as `Shipping_Calculation`, then click `Create New Branch`

![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0131EN-SkillsNetwork/labs/Practice_Project/images/create-branch-1.png)

> This will be used for adding your Shipping Calculation code.

## Task 6: Add the Shipping Calculation code in this branch.

1.  Change to the `Shipping_Calculation` branch by selecting it from the dropdown.

![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0131EN-SkillsNetwork/labs/Practice_Project/images/change-branch.png)

2.  Create a new file named `Shipping_Cost_Calculator.py`.
    
3.  Add the following code in the new file:
    

 # Shipping Cost Calculator`

## Input package weight and shipping rate`
weight = float(input("Enter the package weight in kilograms: "))`
rate = float(input("Enter the shipping rate per kilogram: "))`

## Calculate shipping cost`
shipping_cost = weight * rate`

## Display the result`
11.  `print(f"Shipping Cost: {shipping_cost} USD")`

          

4.  Ensure that the radio button to **Commit directly to the Shipping_Calculation branch** is selected and click `Commit changes`.

![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0131EN-SkillsNetwork/labs/Practice_Project/images/commit-shipping-calculation.png)

The `Shipping_Calculation` branch now contains the `Shipping_Cost_Calculator.py` file.

## Task 7: Create a pull request to the main branch.

1.  Go to the `Pull request` tab and click on `Compare & pull request`.

![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0131EN-SkillsNetwork/labs/Practice_Project/images/compare-pull.png)

2.  Add an appropriate commit message and click on `Create pull request`.

![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0131EN-SkillsNetwork/labs/Practice_Project/images/commit-message.png)  
  

## Task 8: Merge the branch to the main branch.

1.  Click on `Merge pull request`.

![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0131EN-SkillsNetwork/labs/Practice_Project/images/merge-pull-request.png)  
  

2.  Click on `Confirm merge`.
    
3.  The successfully merged changes will be shown in the Github UI as below:
    

![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0131EN-SkillsNetwork/labs/Practice_Project/images/merge-success.png)  
  

4.  You will see the below message once the branch is merged.

![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0131EN-SkillsNetwork/labs/Practice_Project/images/shipping-py_merged-to-master-01.png)  
  

5.  Check to see that your project now contains the `Shipping_Cost_Calculator.py` file as well.

![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0131EN-SkillsNetwork/labs/Practice_Project/images/shipping-py_merged-to-master-02.png)  
  

# Creadits to:
## Author(s)

#### Nikesh Kumar

#### K Sundararajan

![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-CD0131EN-SkillsNetwork/images/footerlogo.png)
