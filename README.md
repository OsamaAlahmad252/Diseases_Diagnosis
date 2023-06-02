# Diseases_Diagnosis
Diseases Diagnosis with JavaFX

1) You have to add the libraries from Lib folder to your platform, In Eclipse:
   go to: Windows --> Preferences --> Java --> Build Path --> User Libraries --> New 
   and name it as you want, and go to: Add External JREs  
   and got to Lib folder and select each library
   
2) click right button on the project --> Build Path --> Confirure Build Path --> Libraries --> Classpath
   and then add libraries
   
3) after Run for the first time: go to -> Run As -> Run Configuration -> Choose The main class -> Arguments -> VM Arguments
  and then write: --module-path   "\path\to\javafx-sdk-11\lib" --add-modules javafx.controls,javafx.fxml
