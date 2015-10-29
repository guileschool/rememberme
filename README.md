# RememberMe

## What
RememberMe is an email reminder system. It assists by sending you an email at a configurable interval. The email will be from your account, to your account. The ‘reply-to’ field is set such that replying to that email will send the message to whom you have selected in the configuration.

For example, I might want to be reminded to send an email to Mom every Monday at 7AM while I am riding the bus to work. At that time, a reminder email will appear in my inbox, and by replying to that email, I will be sending an email to her.

Play with the script a bit. You will be the only one to see the emails that it creates.

## Installing
Install the script [here](https://script.google.com/macros/s/AKfycbza4-Ue0CaRQevhEWJ6WpcerTlXlSYK1Un74-wn8a7iBY8rwYu5/exec).

**Tip:** Bookmark the installation link, you’ll need to revisit it to make changes.

#### Permissions
During installation the script will ask permissions for the following:

1. Know who you are on Google
2. View your email address
3. View and manage data associated with the application
4. Allow this application to run when you are not present
5. Send email as you

Requests 1,2: Allows the script to determine the address of the current user (eg. you) because all emails will be sent back to your address.

Requests 3: Allows the script to save your settings.

Request 4: Allows the script to set triggers to wake up and send emails at the correct times.

Request 5: Allows the script to send email to you.

**NOTE:** The script does not have access to your entire inbox.

## Configuration
Revisit the install link to configure.

## Uninstalling
Uninstall the script [here](https://script.google.com/macros/s/AKfycbza4-Ue0CaRQevhEWJ6WpcerTlXlSYK1Un74-wn8a7iBY8rwYu5/manage/uninstall)

[Advanced users: View the installed triggers by the script [here](https://script.google.com/macros/triggers?id=MrBIrlX3Ctb1bRUehVYD15C6lgTFfYko9)]

## Questions / Issues
Questions and discussion: [RememberMeScript Google Group](https://groups.google.com/forum/#!forum/remembermescript).

File issues [here](https://github.com/blairkutz/rememberme/issues)

## Why
With current social media tools, it is very easy to become overwhelmed by content. But remembering to email an old friend or loved one can be hard. RememberMe solves that by having reminders show up in your inbox. By simply replying to an email connections can be maintained.

The inspiration from this project came from my late cousin, [Jeremy Monnett](https://www.google.com/search?q=Jeremy%20Monnett). Jeremy was killed in a plane crash in 2015. He was an amazing person in every way. He left behind his wife and two young boys. I realized that we can’t keep these types of accidents from happening but the more we can leave behind of who we are, the better off the world will be.

I now have an email address for my three young girls. Multiple times a week I use RememberMe to send them an email of what they said, did and things that I’m thinking about. Hopefully one day it will be a window into their childhood and their Dad.

## Details of how it works
RememberMe runs on a framework called [Google Apps Scripts](https://developers.google.com/apps-script/?hl=en). It’s a really cool way to programatically access Google services (such as Gmail, Google Calendar, Google Docs/Spreadsheets, etc).

Using something called a [trigger](https://developers.google.com/apps-script/guides/triggers/) the script wakes up at a specific date/time you have configured. It then sends an email from your account to your account. The [reply-to](https://en.wikipedia.org/wiki/Email#Header_fields) field is set such that replying to that email will send the message to whom you have selected in the configuration.

## Code
Source code for this project is open source and posted [here](https://github.com/blairkutz/rememberme).

You can also view and host the Google Script itself [here](https://script.google.com/d/1MyWWhQJEwwIVtzO1lLsbALmvAYFFRmhtA_uUnoYmu-mewIrYnoHmWfmr/edit?usp=sharing).