# Offline Event Storage

Offline event storage is a web based application that works basically with Google Calendar API and HTML5 LocalStorage API.

We know the advantages of Google Calendar. It helps us to scribble down anything and everything that we may forget after sometimes. It helps us to create events and also we can invite our friends to the event using Google Calendar. But sometimes we may gone through a situation like the network suddenly goes down when we were creating some events. Our event will not be saved. So we need to add create that event once again when the network came up again. It is very difficult in places where there are network problems. 


> The main thought behind this application was to store the event locally on Local Storage of borwser using HTML5 LocalStorage API. So that even when the network went down, our event will be saved locally and it will be added to the Google Calendar at the time when the network came up without any complexities.

### Tech

The application uses a number of open source projects to work properly:

* [HTML5] - For a propoer presentation of webpage at client side.
* [Brackets Editor] - HTML/CSS based text editor.
* [JavaScript] - For runtime validations, creation and handling of events.
* [Bootstrap] - light weight framework for HTML designers.
* [Ajax] - For accessing the Google Calendar API.

And of course Offline Google Calender itself is open source with a [public repository](https://github.com/abinthaha/Offline-event) on GitHub.

### Working

   1. When you open the page for the first time, it will asks your permission to access your google account. So click on the 'Authorize' button. You need to do this only once, never again.
   2. You will need to login to your Google account inorder for this app to access your Google Calendar.
   3. After doing the above procedures, you can actually see your default Google Calendar in the application and from there you can see the upcoming events.
   4. In the form, by filing the neccessery fields, you can actually create an event and add it to your Google Calendar.
   5. The event that you created will actually create an event in the original calender if there is network and it will be stord in Local Storage if the network is down.

### API
  1. Google Calendar API.
  2. HTML5 WebStorage API.

##### Google Calendar API
Google Calendar API is one of the most promising and useful API. Google Calendar API lets you display, create and modify calendar events as well as work with many other calendar-related objects, such as calendars or access controls.

###### Advantages
   1. Smart Scheduling for meeting.
   2. Access from your laptop, tablet or mobile.

##### HTML5 WebStorage API
WebStorage API is a new API that is integrated with HTML5. We have been using Cookies for storing a key/value pair locally since the invetion of HTML5.
But in HTML5, we are using a special API called WebStorage API to store the key/value pair locally in a browser. Basically the storage space in not limitted. WebStorage is devided into two, LocalStorage API (which won't destroy even we close the browser) and SessionStorage API (which will be destroyed if we close the browser).

See the site from here : - [Google Calendar Offline](http://abinthaha.github.io/Offline-event/)

