#  Core PHP Project

# Instructions
Use Bootstrap or similar framework as Frontend base. Allowed to use datatables
# Database
Auth with different Roles : Admin, Registered User, Guest
We need to store all Events with fields : Title, Description, Date, Categories (multiple assignable), Location (single selectable). All fields are required except categories.
Comments to Event are allowed by Admin and registered users.
# FrontEnd
/categories page
Fields to show : Name, Events count
Only Admin accessible and all CRUD operations.
/locations page
Fields to show : Name, Events count
Only Admin accessible and all CRUD operations. Restrict admin to delete any location if it is assigned to any Event.
/events page
Viewable for all
Edit/Delete option only for Admin.
Search by name and date.
Filter by Category and Locations.
event/{slug} page
Viewable for all
Show All Events fields.
Comments hierarchy.
Comment Form to show only for Admin and Registered User.
