# zenRepo
Repository of my open source projects

The following projects are currently checked in

1. ZenMdm - . 
   This is a Mobile Device Management opensource project. The first version of this project only deals with handling Android devices.
   Aim is to provide a solution where a device health can be continuously monitored and the user gets exclusive remote excess to monitor the 
   health of his android device.
   
   This project has 3 sub projects
     a) Android - This is the android app that needs to be installed on the device. This would internally keep on sending the health data 
        to the backend service. It also provides a UI to show general health (battery life) etc to the users.
        
      b) Core project - handles the core middleware code. This part can be deployed on the cloud also AWS etc. Currently the datastore
         used is mysql but the DAO's can be configured to the talk to an Amazon SimpleDB etc instance.
         
      c) UI app - this is the desktop version of hte app. This has slightly old code on Adobe flex. If time permits i will por the code 
         to angularjs.
        
        Currently the code is very much in progress. I work on it as and when i get the time :). 