# foodStand
You will need to have your project approved before you can begin coding. In order to move into the coding phase of your project, you should provide the following:

<!-- problem statement:
a concise description of an issue to be addressed or a condition to be improved upon.
who? what? where? why? when?
Think a short paragraph no more than 3 sentences. -->
Many resources for helping people in food unstable situations go underused or lack a central repository the average person can access. Our app provides a simple intuative interface for finding free food resources around you.

<!-- ERD -->
*See trello board

<!-- server route plan -->
GET
    ('/')
         - Res: should send user all unfiltered data
         - Req: empty

POST
    ('/')
         - allows the admin to create a new distro site in the database

PATCH
    ('/:id')
         -allows admin to ammend existing data

DELETE
    ('/:id')
          - removes individual distro site from database

<!-- list of technologies you plan to use, including APIs -->
django
geopy
postgresQL
postGIS
google places

<!-- detailed wireframes for each page of your application -->
*See trello board

<!-- color palette -->
*See trello board

<!-- user-centered stories that identify MVP and Stretch stories -->
*See trello board

<!-- link to your planning tool (such as Pivotal Tracker, Trello, or Waffle) -->
https://trello.com/invite/b/roAps2eR/dd8a36f1d8213ed830ed7c903c305cb2/food-stand