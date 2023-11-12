# ChroniConnect

This is a solution for the [Junction 2023](https://www.junction2023.com/)
Tietoevry challenge
[#PainMgmt](https://www.junction2023.com/challenges-2023/tietoevry).

People experiencing chronic pain feel excluded from society, because they don't
have access to people going through similar experiences. Our application will
create groups of similar people with medical professional supervision, provide
positive individual reinforcement, and reduce opioid usage. In addition, the app
allows tracking of pain and medicine dosage daily, so the patient can easily
track their progress.

The app is publicly available at https://tuskaproject-b09f5.web.app

It is a SPA made with React + Material UI + TypeScript, bundled with Vite and
deployed to Firebase.

## Development

To start developing the app, make sure you have [Node](https://nodejs.org/en/)
installed.

Install dependencies:

```
npm i
```

Start the development environment

```
npm run dev
```

## Deployment

Deployment is done manually to [Firebase](https://firebase.google.com/).

To publish the app, you need to have the Firebase CLI tools installed

```
npm i -g firebase
```

And all dependencies installed

```
npm i
```

And valid credentials for a Google account which is hosting the app.

Then run the `publish` command (build the app, login to Firebase and deploy the
site)

```
npm run publish
```
