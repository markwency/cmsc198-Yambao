# June Week 2

## Todo

- Finish the layout for OSA website (static).
- Make the layout for OSA website in MVC and use Fat-Free Framework.
- Use Google authentication so user can log in on the OSA website I created. User can only use up.edu.ph. If their Google id is not retrieved from the database, redirect to update information page. There, user can fill up information about him/herself. Information is then saved and can be viewed and updated when the user wants to.
- Finish the mini project (create a program that deletes "malicious" files from a USB when said device is plugged. File extensions such as .sh, .ini, .dll, .bat should be removed from the device. Any programming language can be used).

## Done

- Finished the layout for OSA website. Used mainly Materialize CSS Framework and some javascript. Made it responsive as much as possible. Hours Finished: 10
- Converted the static OSA website to MVC and used Fat-Free framework. Hours Finished: 3
- Finished creating a program that deletes certain files in a inserted USB disk. The C program I created last week was a deadend since it was hard to get the path file from a newly inserted USB disk. I then used batch file to constantly check if a removable drive exist, if yes then delete all files with the extension .ini, .bat, .dll, and .sh. The program traverses all directories recursively so it can find all files. If there is no removable drive, repeat the batch file. The batch file is hidden and can only be deleted through the task manager. Hours Finished: 4
- Finished the Google authentication of the OSA website I created. The user can opt to log in using his/her up.edu.ph account. If other account is used (like @gmail.com), prompt the user then automatically log out. After a successful log in using a valid account, a session is created and the Google id is searched in the database. If the Google id does not exist, redirect to update information page. User needs to fill up the information form and can submit the form which then saves it to the database (also saves the Google id). If a user already has an information in the database, the update information page is preloaded with the user's information. User can also log out which clears the session. Hours finished: 16 hours

## To be done

- Adjust the layout according to the comments of our supervisors. Changing the banner, page's layout and font types.
- Apply regex to the form in the update information page so only valid inputs can be placed.
- Improve login modal that pops up when the user wants to log in and the general body of the welcome page.

## Things learned

- I learned how to create a session using the F3 Framework. I also had the experience to submit and retrieve from the database using the same network.
- I learned new things from the Materialize Framework like carousel, sliders and other medias.
- I learned how to create a batch program and vbs files. 
- I learned how to utilize the Google+ api and authenticate. I also managed to acquire the Google id, fullname, email, etc. from Google.

## Hardest task done this week

- It was hard for me to create a Google authentication for the OSA website since it was my first time to use the Google+ api. Fortunately, the Google+ api is well documented therefore the difficulty is lessened. After trying examples, I managed to acquire different information for Google which I then used for the database.