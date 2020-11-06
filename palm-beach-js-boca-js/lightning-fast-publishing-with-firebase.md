# Lightning-Fast Publishing with Firebase

> **Todd Albert, Instructor at Boca Code**

* Google Cloud is 4–20x faster than AWS, Azure, and Rackspace
  * Infrastructure is unmatched
  * Much easier to use than competitors
* Firebase gives you the ease of usability you get with services like Heroku and Netlify with the power of Google
* Google Cloud and Firebase share several services, but they each offer their own solutions
  * They play well together
* Firebase hosting: fast and secure hosting for your web app, static and dynamic content, and microservices
  * The future of Google Cloud
* Why Firebase?
  * Super-fast deploy
  * Super-easy setup
  * Scaling and security
  * Managed by Google
  * Free tier
* Pricing
  * Spark: free
  * Blaze: pay as you go with free tier usage included \(which is enough for almost every application\)

## Setup

### Install firebase command line tools

```bash
npm install -g firebase-tools
```

### Login

```bash
firebase login
```

_\*Only have to do the above once._

### Setup project

```bash
firebase init
```

Choose hosting

Create or choose a project

It automatically creates: a folder to hold the public files \(`public`\), a 404 page \(`404.html`\), a home page \(`index.html`\), `.firebaserc`, `.gitignore`, and `firebase.json`.

`firebase serve` will spin up a server.

`firebase console` will open the project's console in the browser.

Here you can add a custom domain name among other things.

See your release history.

### Deploy

```bash
firebase deploy
```

Set environments in the `.firebaserc` file. Set `default` value to `"development"` so you don't accidentally deploy to staging or production.

Can add a flag

The default hosting URL is `<project-name>.web.app`.

Test for server response time by running the following in the terminal:

```bash
hey -c 100 -z 30s <url>
```

## Questions

* Which database do you use? Cloud Firestore or Realtime Database?
  * Firestore is the better option for most projects because it scales
  * Realtime is good if you need your data instantaneously

