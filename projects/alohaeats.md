---
layout: project
type: project
image: img/calc.png
title: "Aloha Eats"
date: 2023
published: false
labels:
  - Meteor
  - React
summary: "A web application designed for the ICS 314 Final Project"
---
## Overview
Aloha Eats is a web application designed for both vendors and customers in the food industry at UH Manoa. The application focuses on displaying various food items from different vendors, along with the capability for users to set their cuisine and dietary preferences. 

<img class="img-threshold" src="../img/alohahome.png">

## Key Features
**Food Item Management**: Admin users have the ability to add, edit, or delete food items. Each food item includes details such as name, quantity, cuisine type, availability, and dietary options.

**User Preferences**: Users can set their cuisine and dietary preferences. These preferences are then used to filter the displayed food items, ensuring a personalized experience.

<img class="img-threshold" src="../img/editprefs.png">

**Vendor Management**: Vendors can manage their information and food items. This includes editing details about their offerings and updating their menus.

**Admin Panel**: A dedicated admin panel is available for administrative tasks. Admins can manage vendor information, update food items, and set top picks for the day.

<img class="img-threshold" src="../img/adminpanel.png">

**Map Integration**: The application includes a map feature that shows the location of various vendors, enhancing the user experience by providing geographical context.

**Filtered Views**: Based on user preferences, the application filters food items. If no preferences are set, the app shows a broader range of items. This ensures that users see food items that align with their tastes and dietary restrictions.

<img class="img-threshold" src="../img/bypreferences.png">


**User Account Management**: Users can create accounts, log in, and manage their profiles. This includes setting preferences for cuisines and dietary restrictions. There is also a user profile page, where user's can update their information and add an image. 

## My Contributions
Here is a summary of what I personally contributed to this project:
1. Landing Page: Designed and implemented the landing page, using css styles.
   
2. User Authentication and Account Management: Implemented features for user registration, login, and preferences management, including handling vendor-specific information.

3. Food Item Management: Developed the functionality for admins to manage food items. This includes adding, editing, and deleting items, as well as marking certain items as top picks.

4. User Preferences System: You created a system where users can set their cuisine and dietary preferences. This involved handling user preferences data and ensuring these preferences influence the food items displayed to the user.

5. Admin Panel Development: Developed an admin panel where administrators can manage various aspects of the application, including user accounts, vendor information, and food items.

6. Filtered Views and Custom Queries: Worked on creating filtered views of food items based on user preferences. This involved writing custom queries and logic to filter food items according to user-set preferences.

7. Front-End Development: Front-end development using React.js, including creating various components like food items lists, vendor information, and user preferences forms.

8. Database Schema Design: Designed and defined the database schema for different collections: Foods, UserPreferences, and vendors, utilizing MongoDB and SimpleSchema.

9. Design Implementation: Implemented Bootstrap for responsive design, to make the application accessible and user-friendly across different devices.

10. Error Handling: Worked on error handling in various parts of the application, including form submissions and database operations.

11. User Experience: Made several enhancements to the user interface and experience, including adding confirmation messages, and refining page layouts.

source code: <a href="https://github.com/ManoaMunchies"><i class="large github icon "></i>Project Page</a>
