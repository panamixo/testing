# testing
![alt text](class_diagram_final.png "CommonTasker architecture")

### *CommonTasker architecture*
CommonTasker is a mobile crowdsourcing application developed for the purposes of netcommons in the contect of Community Networks.The structure consists of the entities shown in the Figure. 
By using CommonTasker, users of the app are able to create different types of tasks and execute them. Tasks can be errands, questions or objects. 

The entity User can either be a creator of a task or an executor. Certain information are kept for each user such as their (nick)name, their telephone, their age(checks users for being over 18), the location (useful for executing spatially distributed tasks) and the ID used by the application for recognition of the particular user. 

Creators are users able to create a task i.e. create and post a new errand, create and post a question or create and post an object available for sharing. 


Tasks are grouped into different categories and are presented in the form of lists to the users of the app. Each list item (i.e. task) contains its title, a description, a start and finish time, the location, an accompanying picture and the user that has created the task.

Executors are users able to execute tasks that are created by creators. Executors select the task from the available list items and the different categories available and they accept to attend an errand, answer a question or select available objects shared by the creators.



### *Testing procedure for CommonTasker*


User test scenarios: 


1. Verify whether the application has been launched successfully or not. 

2. Verify whether the splash screen is displayed for time a) too long, b) just enough or c) too small.

3. Verify that the application’s display is adapted to the screen size and all buttons and menus are easily clickable.

4. Check that each screen is appropriately displayed in each display mode (landscape, portrait). 

5. Verify that in the play screen, the back key allows to go back to the start-up screen or not. 





