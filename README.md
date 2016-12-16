# FrontEndDev_Assignment6.2
### Assignment 6.2 of the AcadGild Front End Web Dev Course


Create angular 2 app using angular-cli. Steps to follow:  
● npm install -g angular-cli  
● Generating and serving an Angular2 project via a development server  
ng new PROJECT_NAME cd PROJECT_NAME  
ng serve  
● Generating Components, Directives, Pipes and Services  
You can use the ng generate (or just ng g) command to generate Angular components:  
ng generate component my-new-component  
ng g component my-new-component # using the alias  
components support relative path generation  
if in the directory src/app/feature/ and you run  
ng g component new-cmp  
your component will be generated in src/app/feature/new- cmp  
but if you were to run  
ng g component ../newer-cmp