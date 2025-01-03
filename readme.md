=> react is a library.

=> with react there comes somes additional features or libraries which we need to learn to work.
   Those 2 are-

   1. react + react-dom    -> used for creating or working on web 
   2. react + react-native -> used gor mobile applications.
 
=> while installing node there comes a thing called as 
   
   -> npm means node package manager
   But sometimes we dont want to install it on our system and directly wants to execute it, so there comes an addition later

   -> npx means node package executor

=> 1st way to start a react project

  "npx create-react-app <name>" where create-react-app is a software.

********************* create-react-app ****************************
                    -------------------

   -> it is a utility software that installs all the files and dependencies needed for the running  of our react project.
   -> it bacically installs all the node-modules , public folder and src folder.
   -> inside src folder there is a file known as package.json which contains all the info about the project like

      - name
      - version
      - dependencies and their versions (react, react-dom, react-scripts, web-vitals-which is used to check the performance of the website)

      - scripts like( ** start - npm start - that run the project on the development platform
                   ** build - npm build - which create the final production level code of the   exicting code. This is what we truly deploy
                   ** test - npm test - to test all cases
                   ** eject - npm eject - to detach our project from react so that we can now move to other framework if needed.                
                 )
      - eslintConfig basically resposible for those red lines which showcases improvement places  rather than errors.
      - browserlist - contains all the supprotrd browser list. 

   -> try to use run to start scripts - npm run start / npm rub build.
   -> create-react-app is a good method or software but a bulky one too 
***************************************************************************************     

=> 2nd way to create a react app is to use other utilities like Vite or Parcel.

***********************  Vite  *******************************
                       --------
