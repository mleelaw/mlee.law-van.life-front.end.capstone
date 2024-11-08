# mlee.law-van.life-front.end.capstone

{User Stories}
Given the {role} wants to {intent}
When the {role} {performs action}
Then {describe change in UI}

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
When the user viewing the homepage.
Then the user will see an additional users button on the top right of the navigation bar, and a create new selection on both the hikes and campsites dropdowns.

Given the user is not an admin.
When the user is viewing the homepage and hovers over hikes or campsites on the navigation bar.
Then the user can view the see memories drop down.

    NavBar:
    Given the user is viewing any page and wants to see hiking memories.
    When the user selects the see memories button under the hikes dropdown.
    Then they will be directed to the hike memories page.

    Given the user is viewing any page and wants to see camping memories.
    When the user selects the see memories button under the campsite dropdown.
    Then they will be directed to the campsite memories page.

    Given the user is viewing any page.
    When the user selects the van logo button on the navigation bar.
    Then the user will be directed back to the homepage.

    Given the user is an admin and is viewing any page.
    When the user selects the users button on the navigation bar.
    Then the user will be directed to the user data page.

    Given the user is an admin and wants to create a new hike.
    When the user selects the create new adventure button under the hikes drop down.
    Then the user will be directed to the hike memories page.

    Given the user is an admin and wants to create a new campsite.
    When the user selects the create new adventure button under the campsites drop down.
    Then the user will be directed to the campsites memories page.

HIKE MEMORIES:
Given the user is viewing the hike memories page.
When the user scrolls through the hike memory cards.
Then the user can view all properties of each hike, including the name, location.length,and a short review of the admins experience.

CAMPSITE MEMORIES:
Given the user is viewing the campsite memories page.
When the user scrolls through the campsite memory cards.
Then the user can view all properties of each hike, including the name, location.length,and a short review of the admins experience.

CREATE NEW HIKE (ADMIN):
Given the admin is viewing the create new hike page.
When the admin fills in the required fields needed for the new hike card. (name, location, length, difficulty and review) and then clicks the POST button.
Then the new hike card will be added to the hiking memories display and the create new hikes page will be rerendered.

CREATE NEW CAMPSITE (ADMIN):
Given the admin is viewing the create new campsite page.
When the admin fills in the required fields needed for the new hike card. (name, location, review) and then clicks the POST button.
Then the new campsite card will be added to the campsite memories display and the create new campsite page will be rerendered.

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
