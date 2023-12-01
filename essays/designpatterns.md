---
layout: essay
type: essay
title: "Embracing Design Patterns in Meteor-React and Bootstrap 5"
# All dates must be YYYY-MM-DD format!
date: 2023-11-30
published: true
labels:
  - Engineering
---
*Embracing Design Patterns in Meteor-React and Bootstrap 5*
## The Application of Design Patterns
Design patterns are not unique to software engineering. In a broader context, design patterns act as guidance by providing proven solutions to common problems. Just as a lost hiker might use a map and compass to find his way home, software engineers have reusable tools to guide them to a succesful and maintainable product. Design patterns provide a standardized approach to solve dilemmas that programmers frequently encounter. These are not reusable pieces of code, but rather conceptual frameworks that can be shaped to fit the unique scenarios presented by different problems. Developers use these patterns to create a seamless interaction between different parts of an application.  

## Design Patterns in My Code: Meteor-React and Bootstrap 5
Throughout this semester I have gained experience working with Meteor-React in tandum with Bootstrap 5. Design patterns play a crucial role in the task of creating a web application. In Meteor-React, one of the most important design patterns I have used is the Observer pattern. Meteor maintains and reacts to data changes, while react acts as the observer with its states and props. This allows react to update the UI in realtime by waiting for cues from meteor. 

React's component based architecture is a great example of a Composite pattern. Complex UIs need to be broken down into smaller, reusable components. Compnents help organize the project and greatly reduce the amount of duplicate code. This is crucial in the web application I am working on now. The UI is broken into pages, components, and a layout that manages the routes through the application. The components hold code in a consolidated file that can be re-used across the large number of pages in the project. This gives a clear structure - without the components there would be many lines of duplicated code which would result in an unorganized mess. On top of this, components also increase efficiency. Nobody wants to write almost identical code in ten different files. The resulting modularity makes in trivial to expand and implement more features to the application. 

Lastly, Bootstrap 5's classes act as a Decorator pattern when thrown in the mix with meteor and react. These classes enhance the appearance and functionality of the HTML elements without changing the underlying structure. I have used Bootstrap 5 in my projects to give a responsive feel: for example, the flex container will dynamically change the size and position of components like the navbar to fit any sized screen. This makes it simple to design an application that will work both on desktops and mobile phones. 

## Concluding Thoughts
In conclusion, design patterns are the underlying concepts that bring stucture, efficiency, and elegance to the world of software development. In my experience with Meteor-React and Bootstrap 5, these patterns have been instrumental in creating applications that are not only functional but also maintainable and scalable. They guide the flow and structure of an application, ensuring each component performs in synchronization with the others. I am sure that I will be integrating many more of these design patterns into my future projects.
