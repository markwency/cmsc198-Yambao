# July Week 4

## Todo

- Finalize revisions to our OSA website.
- Apply image uploader just like in original OSA website.
- Add admin user and admin page.

## Done

- Finish applying changes based on our supervisor's comments. I also improved UX on the automated carousel and bulletin slider. Removed unnecessary aesthetics.  Hours Finished: 6
- Sucessfully implemented an image uploader. Image is chosen by the user then saved on the local directory. The file name is randomized and file is checked if it has a valid extension. Also save the pathfile to the database. Hours Finished: 9
- Inserted a new table for admin. Also created a login system for use of the admin only. The login system is located on a page for the admin (restriced access for normal users). The purpose of the admin page is to approve valid pictures uploaded by the user (used currently by the original OSA website). Hours Finished: 8

## To be done

- Find a way to resize an image to 200x200 before uploading.
- Add an approval system that allows the admin to set the valid uploaded picture from the user as the uploader's profile picture.

## Things learned

- I learned how to utilize move_uploaded_file to save the file from an HTML form.

## Hardest task done this week

- Hardest task is implementing an image upload system since I'm not familiar in file uploading using AJAX and Fat-Free Framework.