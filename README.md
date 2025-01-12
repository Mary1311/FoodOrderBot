# FoodOrderBot
 A Microsoft Teams chatbot that simplifies and organizes daily food orders for your team.

# Features

# Employee Features

1. **Daily Notifications**

   - The bot sends a daily notification from Wednesday to Friday to all employees, prompting them to choose their meals.

   - Notifications include a link to the restaurant's menu for that day.
   

2. **Food Selection Form**

   - Employees can select their desired meal through a simple form integrated into Microsoft Teams.
   

3. **Reminders**

   - The bot sends periodic reminders to employees who have not submitted their choices.

   - Employees can opt out of receiving reminders if desired.
   

# Manager Features

1. Admin Panel

   - The manager has access to an admin interface to:

     - Update the restaurant for a specific day.

     - Change the menu or restaurant link dynamically.

     - View and export a summary of food orders for each day.
     - 

2. Custom Restaurant Management

   - The manager can override the default restaurant schedule and set a new restaurant or menu for a specific day.


3. Order Summary

   - Generates a consolidated summary of orders that can be exported as a file (e.g., CSV or Excel) for easy review and sharing.

# Functional Flow

Default Workflow

1. Daily Schedule:

   - Wednesday: Restaurant 1

   - Thursday: Restaurant 2

   - Friday: Restaurant 3
   

2. Bot Notification:

    - Employees receive a message in Teams with the menu link and a prompt to select their meal.
   

3. Order Submission:

   - Employees fill out the form and submit their choice.
   

4. Reminder Notifications:

   - The bot checks for unsubmitted responses and sends reminders at defined intervals.

   - Employees can opt out of reminders.
   

5. Order Consolidation:

   - The manager receives a summary of all orders in the admin dashboard.
   

Admin Overrides

1. The manager updates the restaurant or menu link for a specific day via the admin panel.

2. The bot sends the updated notification to employees.

# Future Enhancements

1. Multi-Language Support

   - Add localization for different languages.

2. Recurring Orders

   - Allow employees to save favorite meals and reorder them easily.

3. Advanced Analytics

   - Provide insights on order trends and preferences.