# Admin Interface and Adding New Journalists


At this point, you (the administrator) should have your own username and password, plus 2 factor authentication through either the Google Authenticator app on your smartphone or a Yubikey. 

Now, you can add create new log-ins for the journalists at your news organization who will be checking the system for submissions. Make sure the journalist is physically in the same room as you when you do this, as they will have to create a password and scan a bar code for their 2 factor authentication. Since you’re logged in, this is the screen you should see now:

![“SecureDrop main page”](images/admin_main_home.png)

In the top right corner click the “Admin” link, which should bring you to this page:

![“SecureDrop admin home”](images/admin_secondary_home.png)

Once there, click ‘Add User’ button, which will take you to this page:

![“Add a new user”](images/admin_add_new_user.png)

Here, you will hand the keyboard over to the journalist so they can create their own username and password. Once they’re done entering a username and password for themselves, select whether you would like them to also be an administrator (this allows them to add or delete other journalist accounts), and whether they will be using a Ubikey for 2 factor authentication. If they are using Google Authenticator for their 2 factor, they can just proceed to the next page. The next page should look like this if they are using Google Authenticator:

![“Enable Google Authenticator”](images/admin_enable_authenticator.png)

At this point, the journalist should make sure they have downloaded the Google authenticator app to their smartphone from the Apple Store on their iPhone or Goolge Play store on their Android phone. Once you download it and open it, the app does not require set up. It should prompt you to scan a barcode. The journalist should scan the barcode on the SecureDrop screen.
Inside the Google authenticator app, a six digit number should appear that recycles to a new number every thirty seconds. Enter the six digit number under “Verification code” at the bottom of the SecureDrop screen here, and hit enter: 

![“Verify Google Authenticator works”](images/admin_enter_verification.png)

Congratulations! You have successfully set up a journalist on SecureDrop. Make sure the journalist remembers their username and password and always has their 2 factor authentication device in their possession when they attempt to log-in to SecureDrop. 
