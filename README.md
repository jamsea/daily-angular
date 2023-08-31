# Daily custom Angular video call app with chat

![Home screen](./assets/home.png)

This sample app demonstrates how to build a Daily video app with [Angular](https://angular.io/) and [`daily-js`](https://github.com/daily-co/daily-js).

## Features

This sample app includes:

- Multi-participant video call functionality
- Media device controls to toggle local video and audio.
- Local chat between participants in the call. (This does not include chat history but that's also possible.)
- Error message if the Daily room does not exist.
- "Page not found" message for routes not covered by this demo.

![Call screen](./assets/call.png)
![Chat shown in call view](./assets/chat.png)
![Error message](./assets/error.png)

It does not include:

- Device selection
- Meeting room access controls (i.e., knocking to enter private rooms)
- Prejoin UI (i.e., a video preview before joining the call)

These can be added, though! :)

## Requirements

To use this sample app, you will need to:

1. Create a Daily account (for free!) at [https://dashboard.daily.co/signup](https://dashboard.daily.co/signup).
2. Create a public Daily room at [https://dashboard.daily.co/rooms/create](https://dashboard.daily.co/rooms/create). You can also use the [REST API](https://docs.daily.co/reference/rest-api/rooms/create-room#example-requests) to do this.

## Run app locally

To run this sample app locally, start by installing the Angular CLI if you haven't already:

```bash
npm install -g @angular/cli
```

Next, run the following commands in your terminal:

```bash
# clone the repo
git clone https://github.com/daily-demos/daily-angular.git
# change directories to local copy
cd daily-angular
# install dependencies
npm install
# start dev server
npm run start
```

Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.
