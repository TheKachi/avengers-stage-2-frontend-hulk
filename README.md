# avengers-stage-2-frontend-hulk

Team Avengers Group 1

This is the frontend repository for the EstyHotels page design.

## Steps to working on this repo.

***1:*** Fork the Repo.

***2:*** Clone the forked copy of the repo.

***3:*** Confirm you are on develop branch.

***4:*** Create a feature branch off develop e.g "git checkout -b home-page".

***5:*** confirm you are on your new created feature branch.

***6:*** When you are done working on the feature branch you can now do the normal workflow and send a PR.

for more information on git workflow kindly look [here](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow)

***7:*** Make your first Pull Request, you have to edit the `CONTRIBUTORS.md` file with your github id in this format

```-  [@USERNAME](https://github.com/USERNAME)``` 

leave a new line between the last name you see there ans yours, just follow the same format as the last person.

## Colors
 - Primary color (orange color on the page): **#D66939**
 - Secondary Color (Black colors on the page): **#2C2C2C**
 - Tertiary color (White text on the page): **#FFFFFF**

## Images

All images on the page can be found in the assets folder and can be accessed from the __index.html__ file using **./assets/img-name.png**. e.g
```html
<img src="./assets/hero-img.png">
```

## Icons

All icons such as the facebook, twitter, email icons can be found in the icons folder under the assets folder and can be accessed using **./assets/icons/icon-name.svg**. e.g
```html
<img src="./assets/icons/logo.svg">
```

## How to contribute

 - Create a fork of this repo by clicking the **fork** button at the top of this page
 - After creating your fork, click on the **clone or download** button to clone the repo to your local computer. (You can choose to copy the url of download ZIP). If you downloaded as ZIP, then you can skip step 3
 - After copying the url, go to your terminal on your computer and type ```git clone 'url you copied'```. Skip steps 4 and 5
 - If you downloaded as ZIP, unzip the file to your preferred location. Copy the url of the repo from the browser and store somewhere.
 - Open up a terminal and navigate to the folder where you unzipped the files and type in the following commands
 ```bash
 $ git init
 $ git remote add origin 'url you copied';
 ```
 - After this, you can then work on you fork locally. When you're ready to push, use the git push -u origin master to push to your master branch
 - Open up browser and go the your repo, you should see a create pull request button.
 - Create the pull request to the original repo and wait for the work to be merged
