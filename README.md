# ITMD443-Vanilla

A basic html structure

## Objective:

Create a simple web application, check it into source control using GitHub, and deploy it to cloud infrastructure using GitHub Actions workflow. Demonstrate CI/CD by making changes to the code, committing it to GitHub, and automatically triggering a deployment to reflect the changes in the cloud.

## Assignment Details:

### Part 1: Setting Up Your Development Environment

1. Ensure you have the following prerequisites installed:
   - Git
   - A code editor (e.g., Visual Studio Code)
   - A GitHub account

### Part 2: Create a Basic Web Application

1. Create a new directory on your local machine for your project.
2. Inside this directory, create an `index.html` file with the following content:

```html
<!DOCTYPE html>
<html lang="en">
    <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My Basic Web Application</title>
    </head>
    <body>
    <h1>Welcome to My Basic Web Application</h1>
    <p>This is a simple HTML file for the CI/CD assignment.</p>
    </body>
</html>
```

3. Initialize a new Git repository in your project directory by running `git init`.
4. Add your `index.html` file to the repository using `git add .` and commit the changes using `git commit -m "Initial commit"`.

### Part 3: Check into Source Control Using GitHub

1. Create a new repository on GitHub and name it appropriately for your project.
2. Link your local repository to your GitHub repository using the instructions provided by GitHub.
3. Push your local commits to the remote repository using `git push`.

### Part 4: Deploy to Cloud Infrastructure Using GitHub Actions

1. In your GitHub repository, create a new directory `.github/workflows/`
2. Define a workflow that performs the following steps:
   - Trigger on push to the main branch.
   - Checkout the code.
   - Install any dependencies (if needed).
   - Deploy to the cloud provider of your choice (e.g., Azure, AWS, GCP, Vercel, Netlify).
   - Ensure that your cloud provider is connected to your GitHub account and is set up to deploy your main branch.

### Part 5: Demonstrate CI/CD

1. Make a change to your `index.html` file .
2. Commit the change to your local repository using `git commit`.
3. Push the change to your GitHub repository using `git push`.
4. Monitor the GitHub Actions workflow to ensure that it runs successfully and deploys your changes to the cloud.

### Part 6: Submission

1. Prepare the following URLs for submission:
   - URL for the GitHub repository (ensure it's public and contains both the baseline code and subsequent changes).
   - URL for the deployed web application (accessible publicly).
2. Submit the assignment by providing the above URLs
3. It is not necessary to upload any files as long as you have valid URLs.

### Evaluation Criteria:

- The GitHub repository contains a clear commit history showing the baseline code and changes made.
- The repository includes a working GitHub Actions workflow file.
- The web application is accessible via the provided URL and reflects the latest changes.
- The student demonstrates an understanding of source control, GitHub Actions, and cloud deployment concepts.
  Good luck with your assignment, and have fun learning about CI/CD in frontend web development!
