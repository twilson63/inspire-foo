# Inspire Foo

A practice application.

This application will be a mobile application that will allow users to generate an inspiring quote when ever they need something inspiring to say to themselves, a friend or a group of people.

The app will consist of a button and when clicked it will generate 6 random quotes each with the ability to tweet, message or text to friends.

If the user wants to tweet or message, we will use the embed button, if they want send a text message, we can use twilio service or aws sms service, or possibly integration with messaging with the device.

* Phase 1 : create an app that has a single button, when you click on it, it will return six inspirational quotes, hard coded.

* Phase 2 : create a redux store and use redux thunk in a create action, that makes 6 calls to the `http://api.forismatic.com/api/1.0/?method=getQuote&format=json&key=6&lang=en` api and will return 6 quotes to display.

* Phase 3 : Allow the user to click on each inspirational saying and view a single page showing the saying and the ability to tweet, message, or sms.

* Phase 4 : create a twitter button component that will allow the user to tweet one of the six messages.

* Phase 5 : create a facebook button component that will allow the user to tweet one of the six messages.

* Phase 6 : create the ability to sms the message to a friend.

* Phase 7 : use keen.io to track and monitor usage

* Phase 8 : deploy to the app stores
