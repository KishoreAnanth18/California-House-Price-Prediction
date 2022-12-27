# California-House-Price-Prediction

## Software and Tools requirements
- [Google Colab](https://colab.research.google.com/)
- [GitHub](https://github.com/)
- [Git CLI](https://git-scm.com/downloads)
- [Visual Studio Code](https://code.visualstudio.com/)
- [Render](https://render.com/)

## Model creation to application deployment

### Create price prediction model
1. Open Google colab or Jupyter Notebook, anything is good for model creation.
2. California_house_price_prediction_ML_project.ipynb file is available in the repository, go through the comments in the file for creating a prediction model and scaler model.
3. Download the model (.pkl) files. 

### Configuration - VS code - GitHub
1. Create a github account.
2. Login to your Account and Create a repository for project.
3. Now clone the repository to local machine using git clone cmd.
4. For this to work, Git CLI have to be installed.
5. In the cloned directory open VS code.
6. The default files in the repository will be avaiable.
7. Now paste the model files into the directory.
8. For now use git commands to push the changes to the repository.

#### Git commands
- git status   |It tells about the change in the directory.
- git add filename (or) git add .    |It add the new files to the directory.
- git commit -m "message"     |It commit the changes in the directory.
- git push origin main     |It push the commits into the repository.

### Flask Application
1. Create a Flask application with the model.
2. Create a html page for front-end.
3. To check if the model working with Flask, use [Postman API Platform](https://www.postman.com/).
4. After successful deployment in the local machine, push the changes to the repository.

### Host the website
1. Create a render account - It's an amazing platform to host websites for free.
2. Connect your GitHub account with the render account.
3. Create a web service and connect with your house price prediction repository.
4. Now deploy the project into the server.

Congratulations🎉 website hosted successfully!
