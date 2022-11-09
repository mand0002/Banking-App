# Banking-App
This app is a project I worked on for MIT's coding bootcamp.  I chose this project as my capstone project for personal reasons.  My husband and I recently bought a bank that was decomissioned during Covid that we are turning into a home/business.  The bank previously had a ATM, which we may reinstall. I doubt that I will ever write my own software for the ATM, but who knows. If nothing else, I may be able to adapt this APP to use with organizing our vault which has about 400 safe deposit boxes that we use for personal storage of valuables.  How cool would it be to have an app on our phone that we can use to verify security of other family members and allow access to things only they are allow to access.  So many ideas.

Installation  
    Create a clone of this project or download all the files.
    Install Docker if you don't already have it installed.
    Sign up for a MongoDB account if you don't already have one.
    Download/Install Studio 3T if you don't have it already.
    Run Docker in any terminal you choose (make sure you are in the root directory for the project) use this code: <docker run -p 27017:27017 --name dal -d mongo>
      NOTE: if you ran Docker and get an error you may need to delete the last container you created using <docker rm /yourLastContainerName>
    Test MongoDB with the following code: <node mongo_test.js>
      In your terminal, you should see a message that says the connection was successful.
    Check the contents of your MongoDB database
      Using Robo 3T connect to the database using localhost:27017 which you will find in mongo_test.js file.
      Check documents to see current or added entries of bank users to the database.
    navigate to localhost:3000 to access the app and test all the features.
    
Technology
    React
    MongoDB
    Docker
    Express
    Studio 3T
  
Features
    Create account page
    login page
    deposit page
    withdraw page
    balance page
    all data page
    
License
  Free
