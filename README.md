# Weekend Challenge 11 - React-Redux Feedback Form

## Instructions

Reviewing code is an important role developers play. We're going to practice reviewing code from others.

- Get the repo url from your partner
- Get your partner's project running on your computer
- Review the code from your partner and give relevant feedback
- Complete the Markdown section and submit that in the notes section on the assignment app. (Make sure you include who's code you reviewed.)

Practicing compassionate code reviews is important (you can learn more from this video on the topic: https://www.youtube.com/watch?v=Ea8EiIPZvh0 )

## Review Checklist

## Base Required Features 

- Multi-Part Form:  
  - [yes] Able to add feedback
    - [yes] Data collected on individual pages & components
    - [yes] Click on next takes you to the next page in sequence
    - [yes] Data saves in DB after *all* the parts are completed (not piecemeal)
    - [yes] Thank you page takes you back to the first view
    - [yes] Old Data is cleared on form completion

- Client code:
  - [yes]  Individual components for each form part
  - [yes]  Redux setup complete
    - [yes] Store linked to react with `<Provider>`
    - [yes] Store setup with reducer(s) and logger middleware 
  - [yes] Reducers & Actions Working
    - [yes] Actions are in SCREAMING_SNAKE_CASE and semantically named
    - [yes] Actions have a `type` key, and `payload` if sending data
    - [yes] Reducers are returning a new state, or the old state (not mutating)
    - [no] Reducers are using spread correctly (to keep old data, while adding new)
  - [] Review Component shows at all times with current redux state
  - [yes] React-Redux Working
    - [yes] Dispatching actions onClick
    - [yes] Grabbing data from the redux store with `useSelector`
  - [yes] Axios POST request to add feedback


- Server code:   
  - [yes] Router made for GET, POST


## General Items

- Git 
  - [yes] Multiple git commits showing incremental progress
  - [yes] Commits are descriptive of the changes made or feature added 
  - [yes] Has .gitignore with node_modules
  - [yes] Readme file updated (assuming this is previously discussed)
- Code Style 
  - [yes] Appropriate amount of code comments
  - [yes] Code is consistently formatted
- Client
  - [yes] Appropriate use of HTML tags
  - [yes] Basic CSS styling with margins/padding


## Stretch Goals
First must be complete for score of _5 - Exceeds Expectations_

- Previous Steps
  - [yes] allows a user to go to a previous step, either directly or by cycling backward thru the steps
  - [yes] user can update their score for a step
    - [yes] new score is validated to not be empty
    - [yes] redux is updated with new score
  - [yes] user can continue on to review page and submit as in Base Mode


- Admin View
  - [yes] All entries are visible with correct data from inputs
    - [no] Most recent is at the top
  - [yes] Can Delete an entry
    - [no] User is prompted before deleting
  - [no] Axios GET request to get all feedback for `/admin` view in componentDidMount

  Busywork Goals, consider removing or making more useful

- [yes] Styling with Material UI
- [no] Ability to flag a feedback item on `/admin` for further review
- [no] Deployed to Heroku


## Markdown

```
Reese, you had done a fantastic job here. The app is running very smoothly, and has some really cool material ui implemented. base mode works perfect, and you did very well on getting the stretch goals completed. 

General Feedback.

---
| Functional Requirements | Complete? |
| --- | :---: |
| Multi page form with client side routing and navigation (next button) | yes |
| Data stored in Redux when navigating from page to page | yes |
| User is notified when trying to leave a blank score | yes |
| Review Component displays scores and comments from current redux state | yes |
| Submit button sends data to the server via Axios | yes |
| Confirmaion Page displays after data is POSTed to the server | yes |
| Button on Confirmation Page clears Redux and starts a new survey | yes |
| Views are broken down into components | yes |

---
### Notes:

You have met all of the base mode specifications to par. Great work!

---
| General Items | Complete? |
| --- | :---: |
| More than 15 git commits | yes |
| Commits are descriptive of the changes made or feature added | yes |
| Readme file updated | yes |
| Appropriate amount of code comments | yes |
| Code is consistently formatted | yes |
| Server code organized with router & module files | yes |

---
### Notes:

I believe your commenting here was solid as it reflects your description of the function logic well in each component. 

```
