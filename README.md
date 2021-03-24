# Ginger Talk

_badges will update soon_

Ginger Talk is a video conferencing service provided by the Ginger Co, which is 100% open source and have tons of features including,

- A Top-notch minimal UI
- End-to-end encryption with advanced video compression technology
- A well precedented API

---
## What's in the doc?

- Create your own Ginger API for testing of this app
- Building and debugging the app
- Exporting app to Web, Windows and Linux machines
- Contributing to Ginger
-- Creating PRs
-- Donations

---


## Why do we use Flutter?
Flutter is Google’s UI toolkit for building beautiful, natively compiled applications for [mobile](https://flutter.dev/docs), [web](https://flutter.dev/web), and [desktop](https://flutter.dev/desktop) from a single codebase.

- Fast Development
Paint your app to life in milliseconds with Stateful Hot Reload. Use a rich set of fully-customizable widgets to build native interfaces in minutes.


- Expressive and Flexible UI
Quickly ship features with a focus on native end-user experiences. Layered architecture allows for full customization, which results in incredibly fast rendering and expressive and flexible designs.


- Native Performance
Flutter’s widgets incorporate all critical platform differences such as scrolling, navigation, icons and fonts, and your Flutter code is compiled to native ARM machine code using
---
## Tech used,

Ginger Talk uses a number of open source projects to work properly:

- _will update soon_

---
## Installation

Ginger requires [Flutter](https://flutter.dev/) v1.2.1 - v2.0 to run.

After installing flutter, clone the Ginger Talk app from the repo

```sh
git clone https://github.com/thegingerco/ginger-talk.git
cd ginger-talk-main
```
Now, we will build the dependencies in order to compile the application,

```sh
flutter upgrade
flutter pub get
flutter doctor -v
```

Now, in order to build an application, we'll

`On Android`
```sh
flutter build apk --release --verbose
```
`On iOS`
`note: you will need XCode in order to make apps for iOS and MacOS`
```flutter
flutter build ipa --release --verbose
```
`On Windows`
```flutter
flutter build windows --x64 --x86 --release
```
`On Linux distros`
```flutter
$ flutter build linux
```
---
## Further Development

Till now, we only discussed to clone and build an app, so, now, we'll discuss to manage APIs and the UI of the app.
For the APIs, Ginger uses varieties of APIs in order to run, this below table lists them all

| Plugin | README |
| ------ | ------ |
| Ginger Main API | [dev.theginger.co](https://developers.theginger.co/api/ginger-api/) |
| Ginger Talk API | [dev.theginger.co](https://developers.theginger.co/api/talk/) |
| OneSignal | [onesignal.com]() |
| Firebase | [firebase.google.com]() |
---
## Editing

Now, you probably want to know how to edit Ginger base app, isn't it?

_The documentation will update soon..._

---
## License

Read [LICENSE.md](LICENSE.md) for more details about Licensing.

---
Contact: 
[hello@theginger.co](mailto:hello@theginger.co)
[hello@maanasnair.in](mailto:hello@maanasnair.in)
[+91 !null](tel:+00)