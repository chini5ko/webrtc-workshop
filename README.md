# webrtc-workshop

Create and deploy your own WebRTC webapp with Google App Engine

# Before the workshop

- create a google cloud console acount [here](https://cloud.google.com/)
  (skip if you have one)

## Install:

- [node.js](https://nodejs.org/en/)
- [Google Cloud SDK](https://cloud.google.com/sdk/docs/install)
- [Visual Studio Code](https://code.visualstudio.com)
- [git bash](https://gitforwindows.org)(for window)

Check that you have installed the following on your terminal:

```
$ node -v
$ npm -v
$ gcloud -v
```

# Running your video webapp locally

### step 0 - (clone the repo)

```
$ git clone https://github.com/chini5ko/webrtc-workshop.git
```

### step 1 - (install dependancy)

```
$ npm install
```

### step 2 - (run your webapp locally)

```
$ node server.js
```

# Deploy it to the world 🌎

1.  craete a Google [App Engine](https://cloud.google.com/appengine) instance

2.  login:

```
$ gcloud auth login
```

3.  fidn your project ID:

```
$ gcloud projects list
```

4.  set your project:

```
$ gcloud config set project PROJECT_ID
```

5. deploy !

```
$ gcloud app deploy
```

6. About your project !

```
gcloud app describe
```

Example: [https://teak-kit-305302.uc.r.appspot.com](https://teak-kit-305302.uc.r.appspot.com)

# After the workshop

checkout [pairstudy.com](https://www.pairstudy.com)

# webrtc resources:

- https://webrtc.org/getting-started/firebase-rtc-codelab
- https://webrtc.github.io/samples/
- [Workshop slide](https://docs.google.com/presentation/d/1oBXDO5dXUtMYLiVKDJbk0vBaue_WWRfXDwsPh6FOeg4/edit?usp=sharing)

##### Note:

Part of this workshop's code was cloned from this [repo](https://github.com/agilityfeat/webrtc-video-conference-tutorial/tree/webrtc)
