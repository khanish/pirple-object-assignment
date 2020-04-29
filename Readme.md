Object Oriented Programming(OOP), is that branch of programming were structures are been seen in the real world sense. In OOP everthing thing that makes sense in the real world is seen as an entity that is they have states and behaviours. In my opinion OOP pattern will be a better choice in situations where by there is a general structure and sub structures needs to have the same properties and even more as the general structure.

In my piont of view a program that can benefit greatly from OOP is a USER-TO-DO-LIST program, since it is program that so much supports the principle of CRUD. 

On a USER-TO-DO-LIST program, the user has the ability to create and store Objects, this objects are the things he/she has to do, he/she also has the ability to delete or update an existing task to be completed or task already completed. These task has as properties(date task was created, title of the task, targeted time to complete task, details about the task and allot), all of these makes up the states of the program also it has behavoiurs the ability to create a new task, read that task and can either update or delete the task.

Using Pseudo Codes to map out the objectives of the application
open home screen() 
    veiw todos titles and their status
    touch todo title()
        view todo detail()
        if touch todo update button()
            open todo update() 
                update todo()
                touch save button()
                update todo
                return view todo detail()
            if torch return button()
                view home screen()
        if touch todo delete button()
            drop todo from todo list
            view home screen()
    touch add todo button = add todo() 
                    enter todo title
                    enter target time
                    enter todo detail
                touch save todo button = savetodo() 
                    register todo title
                    register todo target time
                    register todo tadetail
                    closeAddtodo()
                    view todo detail()




/*
What is object oriented programming, and why would you use it? As you may already know, many javascript projects are written using a functional, or event-driven design pattern. In which cases would an OOP pattern be a better choice?

For this task, write a few paragraphs describing a project that would benefit greatly from an OOP structure. (This could be any kind of application, running on any type of system). Describe the application flow from the user's point of view (user stories). What is the application's purpose, and how would people use it? What information would they enter, and what would be received? Try to mention all the "stories" in which the user performs any kind of CRUD operation.

Next, using pseudocode (or any other notation-technique or diagramming tool you wish), map out what the main objects of the system would look like, how they would be constructed, and how they would relate to each other. 

Save your writeup in a Readme.md file, and push it to Github.


Turning it In:

Zip up your code files and attach them here to receive a grade and continue with the course.

Submit your assignment
You may only submit one file with maximum 100 MB in size
*/