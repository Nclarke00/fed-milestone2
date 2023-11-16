# fed-milestone2

In the Mockup that I have created, I have 4 different sections of ,my list for items that fall into different 
categories(homework, shopping, errands, and misc). The list will also be searchable using the search bar at the 
top. I would also like all of the items in to list to be able to respond to hovering over them by glowing 
different colors based on the category. 
The minimal state representation of my list would probably include Categories and Tasks within those categories.
Each category will have an array associated with it. The arrays will contain the tasks that fall into that
category. The categories themselves I beleive would also be stored in their own array. The state will be stored in
the 'App' component which is the highest-level container. When typing, for example, homework into the search bar
the word homework serves as the key to access the corresponding category and therefore will display its contents 
(front end dev, ux2, Neuroleadership) on the To Do list.
