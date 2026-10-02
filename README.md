# Practice 1.1 - Installing and configuring Web Development Tools

### 2DAW - DWEC Bilingual. 

> **Student Name**:  Fernando Ortega Lomelí

#### Files included in this repository:

Ennumerate and explain each one of the files included in this repo.

- File 1
- File 2
- Etc...

#### Instructions: 

- Fill your name and lastname and answer the questions in the current `README.md` file. You have to submit the activity as a GitHub repo link that has to include the 

- You can add images to this tocument with the syntax:

    ```md
    ![Text to display](link/to/the/image)
    ```

- Any other question about Markdown language you can find in the [Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet/)

### Install and configure VSCode

1. **Install `VSCode` in your computer**.
2. **Create a new folder called `p1.1-frontend-tools`and open it as a workspace in VSCode. Copy the current `README.md` inside it**.
3. **What functionalities do the following VSCode extensions add?**
   - **Bootstrap 5 quick Snippets**
   Gives you ready code for Bootstrap
   - **Live Server**
   Opens your web page in the browser
   - **Prettier**
   Makes your code look clean and neat
   - **Markdown All in One**
    Helps you write .md files
4. **Install the extensions listed in the previous point in VSCode**.
5. **What other extensions do you know that you consider interesting for developing in JavaScript**?
    - **Live Share:** Lets you code with friends in real time.
    - **Code Runner:** Runs your JavaScript code with one click.
6. **Find in VSCode the option in `Settings` to `Format On Save` and activate it. What effect has this option?**
It will fix your code automatically. It will add spaces, fix lines,etc.

### Create a Hello World in JS

7. **Create an `index.html` file inside your worspace folder.**
8. **Create the basic html structure using the `!` snippet and change the title to 'Hello World'**

    ```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <title>Hello World</title>
    </head>
    <body>
      
    </body>
    </html>
    ```

9. **Create a new file called `app.js` and add this two lines**

    ```js
    console.log("Hello Console!")
    document.body.innerHTML = "<h1>Hello document!<h1>"
    ```

10. **Import the script in your html using one of the techniques explained in class. Explain here the technique, show the code and justify why did you choose this technique**.
    To import the script, you have to put script and then the source to the js.
    ```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <title>Hello World</title>
    </head>
    <body>
      <script src="app.js"></script>
    </body>
    </html>
    ```
    I choose this options because it makes sure the HTML loads first then the script runs

11. **Launch `index.html` in Live Server and check that the script is running. Click right button and select inspect to show the developer tools and take a look on the console.**
    
12. **Change some message in the JS code and sava changes. You can check that Live Server refreshes the web page.**
![Text to display](https://github.com/user-attachments/assets/f1cdd21e-c723-41b8-b90d-ef0c65ee8b35)


### Create a simple form with Bootstrap 4. 

13. **At this point, we are going to create a page called `form.html` starting from the `Bs5-$` template provided by the Bootstrap extension we added. What files does this template import in the html by default?**
    -**Bootstrap CSS**
    -**Bootstrap JS** 
14. **Create a `<div>`with the class `.container` to wrap all the sections in the web page**
  <img width="1032" height="332" alt="image" src="https://github.com/user-attachments/assets/10ec8465-7173-43f7-ba46-06ad0c6bbd0e" />

15. **Add a standard navigation bar inside the nav area using the `bs5-navbar-standard` snippet inside the container**
<img width="672" height="216" alt="image" src="https://github.com/user-attachments/assets/985b3257-fa19-484d-96c3-6031f2b25cef" />

16. **Inside the main area create a form using Bootstrap to collect data from a new user who wants to register at an academy that offers courses. We can copy code from [Bootstrap Documentation](https://getbootstrap.com/docs/5.0/forms/overview/)**. 
<img width="598" height="417" alt="image" src="https://github.com/user-attachments/assets/d21d6ea3-c737-429f-bd35-bfa775516c77" />

### Install Git, and upload your repository to GitHub

17. **Install [git](https://git-scm.com/) in your computer**.
    I already have it downloaded
18. **Init the git repository**
    <img width="721" height="92" alt="image" src="https://github.com/user-attachments/assets/7ca713a0-18c0-45ab-ab5b-71ddfc9fae40" />

19. **Log in to your GitHub account provided by IES Azarquiel**
    <img width="325" height="112" alt="image" src="https://github.com/user-attachments/assets/21054f28-0648-42eb-a647-9126162eea7c" />

20. **Follow the teacher on GitHub at the following link: [https://github.com/jeatzr/](https://github.com/jeatzr/)**
    <img width="415" height="771" alt="image" src="https://github.com/user-attachments/assets/e0c4ebed-9d34-4f8c-a17a-279f2f34207f" />

21. **Create a new empty repository on GitHub named `p1.1-frontend-tools`.**
    <img width="902" height="687" alt="image" src="https://github.com/user-attachments/assets/38327878-489e-44a7-a190-aa70f0695dc0" />

22. **Follow the instructions in the command line provided by GitHub to add your files, create the first commit and push it. Notice that in out case we have to add all files to the staged area with `git add .`, not just`git add README.md`** 
    <img width="721" height="340" alt="image" src="https://github.com/user-attachments/assets/ca238c05-e1ba-4141-b74c-2b8d07d3fcfa" />

23. **To finish, submit the link of your GH repo to the task in our Classroom.**
