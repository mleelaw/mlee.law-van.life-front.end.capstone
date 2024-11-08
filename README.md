# mlee.law-van.life-front.end.capstone

{User Stories}

LOG IN:
Given the user wants to create a login.
When the user selects the register new user button.
Then the user will be directed to the register page.

    REGISTER:
    Given the user wants to create a login.
    When the user fills in the required fields (username, password) and clicks the crete button.
    Then the user will be added to the users database and they will be directed back to the login page.

Given the user already has created login.
When the user fills in the required fields (username, password) and clicks the login button.
Then the user will be directed to the homepage.

HOMEPAGE:
Given the user is an admin.
When the admin viewing the homepage.
Then the admin will see an additional users button on the top right of the navigation bar, and a create new entry on hikes.

Given the user is not an admin.
When the user is viewing the homepage and hovers over hikes on the navigation bar.
Then the user can view the see memories drop down.

    NavBar:
    Given the user is viewing any page and wants to see hiking memories.
    When the user selects the see memories button under the hikes dropdown.
    Then they will be directed to the hike memories page.

    Given the user is viewing any page.
    When the user selects the van logo button on the navigation bar.
    Then the user will be directed back to the homepage.

    Given the user is an admin and is viewing any page.
    When the user selects the users button on the navigation bar.
    Then the user will be directed to the user data page.

    Given the user is an admin and wants to create a new hike.
    When the user selects the create new adventure button under the hikes drop down.
    Then the user will be directed to the hike memories page.

HIKE MEMORIES:
Given the user is viewing the hike memories page.
When the user scrolls through the hike memory cards.
Then the user can view all properties of each hike, including the name, location.length,and a short review of the admins experience.

Given the admin is viewing the hike memories page.
When the admin selects the edit button on a hike card.
Then the admin will be directed to the create new hike page where the hike properties will display within the fields to be edited.

Given the admin is viewing the hike memories page.
When the admin selects the delete button on a hike card.
Then the page will render and the hike object wil be deleted from the database.

CREATE NEW HIKE (ADMIN):
Given the admin is viewing the create new hike page.
When the admin fills in the required fields needed for the new hike card. (name, location, length, difficulty and review) and then clicks the POST button.
Then the new hike card will be added to the hiking memories display and the create new hikes page will be rerendered.

USERS (ADMIN):
Given the admin wishes to create a new user.
When the admin fills in the required fields inside of the new user box and selects the create button.
Then the users page will be rerendered and the new user will be added to the user list.

Given the admin wishes to edit an existing user.
When the admin selects the edit button on an existing user in the user list.
Then the users properties will display in the edit user box for the admin to adjust.

Given the admin wishes to save changes to an edit user.
When the admin selects the save button inside of the edit user box.
Then the users page will be rerendered and thew edited user will be rerendered on the user list.

Given the admin wants to delete a user.
When the admin selects the trashcan icon next to a user on the user list.
Then the user will be deleted from the database and the user page will rerender to display the updated user list.
