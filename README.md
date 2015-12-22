# AutoVote
Automatically votes for Edison, refreshes the page, and repeats.


#### Step 1 - Get Tampermonkey for Chrome
To use this code, you will need to install Tampermonkey (if you are using Chrome as your browser). If you already have Tampermonkey, proceed to Step 2.

Tampermonkey: https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo?hl=en

Once Tampermonkey has been installed, an icon should appear in the top right corner of your Chrome browsing window; the icon is a black square with two gray circles on the bottom.

#### Step 2 - Prepare a New Script pad in Tampermonkey
Left click on the Tampermonkey icon in your Chrome browsing window, and a menu should pop-down from the icon. The menu has two columns of options. In the right column, at the bottom, you will find the "Add a user script..." option. Left click it once, and a new tab will open in your current browsing window. In the new tab, you should see some code; on line 2 of that code, you should see 
"// @name    New Userscript". Highlight all of the code in that window (line 1-13) and Delete it. There should now only be a "1" displayed for the line number.

#### Step 3 - Acquire the Scipt code from GitHub
Leave the new Tampermonkey tab open. Above this ReadMe you will see three links entitled (from top to bottom) "AutoVote script", "LICENSE", and "README.md". Open the "AutoVote script" in a new tab, either by Ctrl+Left clicking on the link, or by right clicking on the link and selecting the "Open link in new tab" option. A new tab will open with some code on it; near the top of the code (on line 2) you should see "// @name   Milan Edison - 3 sec" which is the name of the script you are about to install. On the right side of the window which contains the code you should see three buttons entitled "Raw", "Blame", and "History". Left click the "Raw" button and the page will change so that only the code is showing. Highlight all of the code that is displayed in this window, and copy it. 

#### Step 4 - Save new  in Tampermonkey
Navigate back to the Tampermonkey tab that you opened in Step 2, and paste the code that you just copied. Save the script (either by clicking on the floppy disc icon at the top of the code window, or by pressing Ctrl+s on your keyboard). When you do so, a message will appear at the top of the screen with a green check and a message that says "Operation completed successfully". Saving the script may have caused you to be directed to a new page in Tampermonkey, called the Dashboard. If not, after you have saved your script, click on the Close button above the script (a red circle icon, to the right of the Save button). You will now be on the Tampermonkey Dashboard.

#### Step 5 - Use the new script
On the Dashboard, you should see your new script, entitled "Milan Edison - 5 sec vote", with a green "1" button on its left. If you click the green button, it turns to a red square which indicates that the script is off and will not run. If you click it red square, it turns back to a green circle, indicating that the scrip is on and will run when it is appropriate to do so. On the right side of the Dashboard, under the Homepage column, there is a small green button with a house in it. 

To use your new script, simply click on that green button; a new tab will open directly to the voting page and the script will automatically start running. The script continues to run on the page, even if it is not the active tab. You could open several tabs on the voting page, and the script will run on all of them simultaneously. It will continue to run until either the tab(s) is closed, or the script is deactivated.

##### Deactivating the script
The easiest way to deactivate the script is from the Dashboard. To get to the Dashboard, click on the Tampermonkey button at the top right side of your Chrome browser causing the menu to drop down. Near the bottom of the left column of the menu is the "Dashboard" option. Left click it once, and the Tampermonkey Dashboard will open in a new tab. As stated previously, simply click on the green circular "1" button next to the script to deactivate the script (and causing the green circle button to turn into a red square). With the scripte deactiveated, it will stop running on the voting pages as soon as it completes its current iteration.


# "Help! I'm lost!"
If these instructions aren't clear, or if you need assistance, feel free to message me and I will help you implement the script.
