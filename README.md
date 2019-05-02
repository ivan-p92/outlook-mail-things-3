# Outlook Mail and Things3 Alfred integration
After starting using Things3 at work, I was looking for a solution to save Outlook mails to Things3 to follow up on them later. Although some AppleScripts were floating around already, none did what I ultimately wanted: just hitting a shortcut when in Outlook to trigger a Quick Entry with a pre-filled title and some kind of reference to the mail, then – from Things3 – hitting the same shortcut to open and show the original mail in Outlook.

In this tiny repo you will find two AppleScripts. 
One saves the currently selected mail in Outlook to Things3 by triggering a Quick Entry. Its title is of the format **Follow up on 'email subject'**, while the entry's details get pre-filled with the mail's unique id in the format **[mailID:12345]**. Any other content can be added to the todo's description (although I didn't test that extensively).
The other script looks at the currently selected todo in Things3, then opens the original mail in Outlook by using the saved ID.
  
Since I own the Alfred PowerPack I created an Alfred Workflow to run the scripts when hitting **ctrl-option-cmd-M**.
The same can be achieved with BetterTouchTool and probably many more tools. The workflow is included above.

These little scripts are provided as is, free to use in any way, let's say under the gpl-3.0 license. I hope you will find them useful.
