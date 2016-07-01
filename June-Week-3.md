# June Week 3

## Todo

- Create a login system to our OSA Website and apply changes based on comments from our supervisor (layout changes, font styles, improved login modal). Also let the user change his/her password in the account information page.
- Create a function in javascript that will check if a user's given Facebook ID or username in the account information form is valid. User won't need to login in Facebook, just verify if the id or username is existing.
- Apply regex and conditions in the account information form before letting the user submit the form.

## Done

- Applied the desired changes of our supervisor to the website's aesthetics, both the home page and the account information page. Also included a login system where the user can create an account by logging in using his/her up.edu.ph Google account then later on use the username and password of the OSA account for logging in instead of the Google account (user can choose to log in using his/her OSA username or Google email to access his/her account). Inserted a change password input form in the account information page. Password input form will change if the user is new or not. If new, then username and password is required. Else, user can opt not to change his/her username or password. Also made a function to check if a username provided by a user (either new or not) already exists. For the password, I used MD5 and salting. Hours Finished: 20
- Successfully implemented a Facebook ID/username verifier using javascript. I used graph.facebook.com to check if an ID belongs to a Facebook user. For the username, I used PHP to visit the given username's Facebook page then used get_contents and looked for the page's title, then check if the page title is not "Page Not Found". Hours Finished: 6
- Applied regex to the form in the account information page based on the requirements in the original form in the OSA website. Check if name, mobile number, landline number is valid then check if information in required fields are provided. Made sure there are no bugs and loopholes in the form validation. Hours Finished: 6

## To be done

- Add final revisions to the website based on our supervisor's comment on this week's progress report.
- Apply an image uploading system just like in OSA's website.

## Things learned

- I learned how to use the Facebook Graph API.
- I learned new things about Fat-Free Framework sessions.
- I learned different ways of form validation.

## Hardest task done this week

- Hardest task is the Facebook ID/username verifier. The ID is easy to verify since the graph.facebook.com can be used, but since Facebook login can't be used the username is hard to verify (username is not available in the graph.facebook.com for security purposes). I had to think of a way to check if a username exist. Then I tried accessing valid and invalid username pages (www.facebook.com/{insertusernamehere}). Invalid pages had "Page not found" title while valid ones has the name of the user on it. I used that as my algorithm to check if a username is valid. 