# Switch From iPhone Siri To Mac Siri

Have you ever had a problem that you wanted to turn on Siri on a Mac but it turned on your iPhone instead?

Thanks to this method, you will not have such a problem anymore.

## How it works

When you say "Hey siri" and it turns on the iPhone just say "Switch To Mac" and Siri will switch to Mac immediately.


## How To Set Up Or [YouTube Tutorial](https://youtu.be/cHg-KNfGTNM)

* Settings on iPhone
	1. open **Settings** app
	2. scroll down to **Shortcuts**
	3. go to **Advanced**
	4. enable **Allow Running Scripts**
* Settings on Mac
	1. choose **Apple Icon** in the menu bar
	2. select **System Preferences**
	3. go to **Sharing**
	4. select the **Remote Login** checkbox
	5. you should see line with **"example@1.2.3.4"** remember it.

#### Create shortcut

This step can be done on both iPhone and Mac

* On Mac
	1. open **Shortcuts** app
	2. go to **All Shortcuts** folder
	3. click **Add** button
	4. click **Shortcut Name** and type in whatever name you want (e.g. Switch To Mac)
	5. search for **"Run Script Over SSH"** in the search field and double-click it
	6. in the **Script** filed enter `open -a Siri.app`
	7. in the **Host** filed enter numbers from the remembered line (e.g 1.2.3.4)
	8. in the **User** field enter your username from the remembered line (e.g example) 
	9. in the **Password** field enter your Mac password
	10. You can quit **Shortcuts** app
* Or On iPhone
	1. open **Shortcuts** app
	2. go to **All Shortcuts** folder
	3. click **Add** button
	4. click **New Shortcut** > **Rename** and type in whatever name you want (e.g. Switch To Mac)
	5. click **Add Action** and search for **"Run Script Over SSH"** in the search field and click it
	6. in the **Script** filed enter `open -a Siri.app`
	7. in the **Host** filed enter numbers from the remembered line (e.g 1.2.3.4)
	8. in the **User** field enter your username from the remembered line (e.g example) 
	9. in the **Password** field enter your Mac password
	10. click **Done**
	11. you can quit **Shortcuts** app
