# omnifocus-weekly-report
Omnifocus-weekly-report is an omnifocus plugin, it generates weekly report in markdown format, and email it.
## Customization
Omnifocus-weekly-report covers tasks in all folders in default, but you can specify which folder should be included by alter some constants at the head part of this plugin code.

Also you can customize the email address To/Cc, and the subtitles.

Default:
``` javascript
const completedTitle = "COMPLETED"
const todoTitle = "NEXT WEEK"

const targetFolderName = null
const emailTo = ""
const emailCc = "" 
```

Customization:
``` javascript
const completedTitle = "COMPLETED THIS WEEK"
const todoTitle = "TASKS NEXT WEEK"

const targetFolderName = "my company name"
const emailTo = "someone@mycompany.com"
const emailCc = "otherone@mycompany.com" 
```