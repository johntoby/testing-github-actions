# Word Counter

Hi 👋

This is a word counter built with HTML, CSS and JavaScript. It simply counts the number of words you have in your text. This is useful when writing your essays, statement of purpose etc for graduate scholl application that have limit of 800 words or 100 words. Simply copy essay and it will show you how many words you have written in your essay.


## How to use

Although this is a very simple frontend application, for practice, it is meant to be dockerized using a `Dockerfile` to create an image for this application. It will be pushed to Docker hub via github Actions. 

This process makes setting this application up very simple. The following steps can be used to set up this project on your local machine.

- Clone the repository
- Build the Docker image
  ```
  Docker build -t wordcounter .
  ```
- Run the Dockerfile
  ```
  docker run -p 80:80 wordcounter:latest
  ```
 - On your browser, view `localhost`

**Note:**

You have write the text in the text area form and click on the button to count the text. This project's main feature is built using one of JavaScript's string manipulation technique, the `split()` method.

## Project view

![word counter view](/wordcount.JPG)




