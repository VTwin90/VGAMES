# **Milestone 3: V GAMES**

### **Project - Data Centric Development - Code Institute.**
This is the third milestone project from CI with a focus on HTML, CSS, JavaScript, Python+Flask and MongoDB. The point is to build a full-stack site that allows your users to manage a common dataset about a particular domain. Thus V GAMES is a platform to build community and showcase other developers games, in a simple and effective way. 

A deployed link to the website can be found **[here](https://vgames-app.herokuapp.com/)**.

![Mockup]()

## **Contents**
***
- [**User Experience (UX)**](<#user-experience-(ux)>)
  - [Project Goals](<#project-goals>)
  - [Importance and Feasibility chart](<#importance-and-feasibility-chart>)
  - [User Stories](<#user-stories>)
  - [Website Structure](<#website-structure>)
  - [Design Choices from UXD](<#design-choices-from-uxd>)
    - [Color Scheme](<#color-scheme>)
    - [Images](<#images>)
    - [Typography](<#typography>)
  - [Wireframes](<#wireframes>)
  - [Design Changes](<#design-changes>)

- [**Features**](<#features>)
  - [Existing Features](<#existing-features>)
  - [Features left to implement](<#features-left-to-implement>)

- [**Technologies**](<#technologies>)

- [**Testing**](<#testing>)

- [**Deployment**](<#deployment>)

- [**Credits**](<#credits>)

## **User Experience** (UX)
***

### **Project Goals**

### **Importance and Feasibility chart**

**Opportunity/Problem** | **Importance** | **Viability/Feasibility**
| :--- | ---: | :---:
A.   |  | 
B. |  | 
C. |  | 
D. |  | 

#### [Back to top](<#contents>)

### **User stories**

#### **First Time Visitor Goals**
* As a **user** I want to be able to navigate through the whole site smoothly.
* As a **user** I want to understand the purpose of the site upon loading it.
* As a **user** I want the website to be responsive so that I can clearly view the webpages from my mobile, tablet or desktop.
* As a **user**, I want to be able to register to the website so that I can create and manage my own games.

#### **Returning User Goals**
* As a **user** I want to be able to search or filter games based on custom criteria so that I can find games suited to me.
* As a **user** I want to be able to return to the main site without having to use the browser buttons so that I can easily return to the website if I navigate to a page that does not exist.
* As a **user** I want to have some games suggestions.
* As a **user** I want to be able to login and out of my account.
* As a **user** I want to be able to upload a game.
* As a **user** I want to have ease of access to any games that I have already uploaded.
* * As a **user** I want to be able to edit or delete any games that I have already uploaded.

#### **Site Owner Goals**
* As a **site owner** I want to showcase the skills I have learned in HTML, CSS, JavaScript, Python+Flask and MongoDB.
* As a **site owner** I want to be able to add new collections to the site.
* As a **site owner** I want the new collection to be added to the appropriate site areas.
* As a **site owner** I want to be able to edit the pre-existing collections.
* As a **site owner** I want to be able to delete any collections.

#### [Back to top](<#contents>)

### **What is needed now and in the future?**

#### [Back to top](<#contents>)

### **Website Structure**

#### [Back to top](<#contents>)

### **Design Choices from UXD**
***

#### [Back to top](<#contents>)

### **Color Scheme**

### **Images**

### **Typography**

#### [Back to top](<#contents>)

### **Wireframes**

### **Design changes**

#### [Back to top](<#contents>)

## **Features**
***

### **Existing Features**

### **Features Left to Implement**

#### [Back to top](<#contents>)

## **Technologies**
***

### **Languages**

### **Frameworks, Libraries & Programs**

## **Testing**
***

#### [Back to top](<#contents>)

## **Deployment**
***

### **Project Creation**
Navigate to the **[template](https://github.com/Code-Institute-Org/gitpod-full-template)** and click 'Use this template'. Put in Repository name (VGAMES) and check the Include all branches checkbox. Then navigate to the new **[repository](https://github.com/VTwin90/VGAMES)**.

The following commands were used for version control throughout the project:
+ ```git status``` (checks which files have been modified or added, and ready to be committed)
+ ```git add . ``` or ```git add <filename>``` (add all changed files or specific files within the project directory to be committed)
+ ```git commit -m "[TYPE] Reason"``` (commit changes to the local repository)
+ ```git push``` (push all committed changes to the GitHub repository)


### **Deployment to Heroku**
**Create application:**
1. Navigate to Heroku.com and login.
2. Click on the new button.
3. Select create new app.
4. Enter the app name.
5. Select region closest to you.

The live link for the site is here: **[https://vgames-app.herokuapp.com/](https://vgames-app.herokuapp.com/)**

**Set environment variables:**
1. Create a env.py file
2. Insert this information:

```
import os

os.environ.setdefault("IP", "0.0.0.0")
os.environ.setdefault("PORT", "5000")
os.environ.setdefault("SECRET_KEY", " *unique secret key* ")
os.environ.setdefault("MONGO_URI", " *unique uri from mongo.db * ")
os.environ.setdefault("MONGO_DB", " *database name* ")
```

**Note:** Because this contains sensitive information, this needs to be added to the '.gitignore' file. 	

3. Go to MongoDB and to your app database
4. Click the settings tab and then click the Reveal Config Vars button and add the environment variables:

| Key           | Value               |
| ------------- |:--------------------|
| IP            | 0.0.0.0             |
| PORT          | 5000                |
| SECRET_KEY    |*Secure secret key* (to keep client-side sessions secure)  |
| MONGO_URI     | Go to Clusters, Connect and then connect it to your app by giving it the password and DB name that you set up in the link|
| MONGO_DBNAME  |Connect to your database|
|               |                     |

### **Create a local clone**

### **Fork Project**

#### [Back to top](<#contents>)

## **Credits**
***

### **Code**

### **Media & Content**

### **Acknowledgments**

**This project is for educational use only and was created for the Code Institute Module of Interactive Frontend Development.**

**Created by Vanja Torp 2021**

#### [Back to top](<#contents>)