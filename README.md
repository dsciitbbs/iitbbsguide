
# Google Action for [Indian Institute of Technology Bhubaneswar](http://www.iitbbs.ac.in)


## Usage
Invoke action by speaking `Talk to IIT Bhubaneswar Guide` to Google Assistant.

## Supported Actions(tentative)
- Inside Campus Map (ex: Show me direction to SES)

![Screenshot_20190911-152633](https://user-images.githubusercontent.com/25523604/64689638-58282480-d4ac-11e9-8087-371c88fda9ec.png)


- Timetable
- Bus schedule
- BOV schedule
- Upcoming institute holidays (Ex-Show me upcoming holidays)

![Screenshot_20190912-163047](https://user-images.githubusercontent.com/25523604/64779185-09958b80-d57b-11e9-95ed-01fdbfba4a9e.png)

- Mid/End Semester Exam schedule
- Upcoming institute events
- Important Contacts
- Much more to come

## Contributing
- Download the existing code to your local system
```
git clone https://github.com/dsciitbbs/iitbbsguide
```

- Go to the [Activity Controls](https://myaccount.google.com/activitycontrols) page.
Sign in with your Google account, if you have not already done so.
Ensure that the following permissions are enabled: `Web & App Activity, Device Information and Voice & Audio Activity`

- Open the Actions Console > Click New project > Type in a Project name, i.e. "IIT Bhubaneswar Guide".
- Click Create Project.
- Click Build your Action to expand the options and select Add Action(s).
- Click Add your first Action.
- On the Custom intent dialog, click Build to launch the Dialogflow console and click create.
- Click the gear icon on the left navigation and click Export and Import.
- Click Restore From Zip and Upload the downloaded ZIP file.
Type "RESTORE" and click the Restore button and click Done.
- Make the necessary changes and download the ZIP again with the changes and make the Pull Request on this repository.

**Note**: *index.js* is provided as a gist [here](https://gist.github.com/PalAditya/2a995c9871e3b00b1b808af902d1b860) so that you can add it to the fulfillment section (which you'll need for webhook calls and custom payloads, such as opening Google Maps) easily. Just copy and paste :grin:

## Maintainers
- [Aditya Pal](https://github.com/PalAditya/)
- [Aman Pratap Singh](https://github.com/apsknight)
- [Saksham Arneja](https://github.com/arnejasaksham)

## LICENSE
TBD
