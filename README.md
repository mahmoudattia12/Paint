# Paint 
## Contents:
- [Frameworks & technology used](#Frameworks-&-technology-used)
- [How to run](#How-to-run)
- [Used design patterns](#used-design-patterns)
    - [Factory design pattern](#Factory-design-pattern)
    - [Prototype design pattern](#Prototype-design-pattern)
- [UML class diagram](#UML-class-diagram)
- [Snapshots of our UI and a user guide](#Snapshots-of-our-UI-and-a-user-guide)
---
## Frameworks & technology used:
> - For the frontend part (view part), we used HTML, CSS, and typescript through angular framework.
> - For the backend (model and controller), we used Java language through spring framework.
---
## How to run:
- Note: Make sure you downloaded NodeJs and Angular-CLI.
> - extract the compressed project folder.
> - Back-end part:
    > - Open the paintBackend folder using IntelliJ IDE or any other IDE, run the PaintBackendApplication.java class on port 9090.
    > - you can change the port from the project resources → application.properties if the 9090 port was already used in your device but in this case, you will need to change it in all http requests in the app.components.ts file on the front-end folder.
> - Front-end part:
    > - Open the paint-frontend folder using visual studio IDE, then open the terminal of the IDE, and write npm install in the terminal.
    > - Then write “ng serve --open” in the terminal to open the project, on port “http://localhost:4200/”-. Note: if you needed to change port 4200 as it was already in use then you will need to change it in the paintBackend folder in the controller class.
    > - Then you can use the paint application and draw whatever you want.

 




