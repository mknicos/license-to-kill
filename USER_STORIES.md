# User Stories

## Viewing the Menu

As someone unfamiliar with the application
I want to see a list of options
So I can continue on

Acceptance Criteria:
  * If the user selects 1, they see "How do you want to add?"
  * If the user selects 2, they see "What is the injury you want to add?"
  * If the user selects 3, they see "Who is injured?"
  * If the user types in anything else, they should see "<input> is an invalid selection"
    and the menu should be shown again.

Usage:
    > ./livin_will_to_die
    What do you want to do?
    1. Add Person
    2. Add Injury
    3. Evaluate Injured Person

## Add Injury

As someone hoping to murder their friends, I want to enter an exhaustive list of potential
injuries so I know when to pull the plug.

Acceptance Criteria:

  * Duplicate injuries cannot be added
  * Unique injuries will be added to the database

Usage:
    > ./livin_will_to_die
    What do you want to do?
    1. Add Person
    2. Add Injury
    3. Evaluate Injured Person
    - 2
    What is the injury you want to add?
    - Decapitation
    Decapitation has been added.
