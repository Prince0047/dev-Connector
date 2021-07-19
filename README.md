# DevConnector

> Social Media Application for developers

This is a MERN stack application for developers to showcase their work, create a profile and post their opinions.

## Quick Start

---

## Add a default.json file in the config folder with the following

```
{
  "mongoURI": "<your_mongoDB_Atlas_uri_with_credentials>",
  "jwtSecret": "secret",
  "githubToken": "<yoursecrectaccesstoken>"
}
```

## Install server dependencies

```
npm install
```

## Install client dependecies

```
cd client
npm install
```

## Run both Express and React from root

```
npm run dev
```

###Build for production

```
cd client
npm run build
```

# Test product before deploy

After running a build in the client 👆, cd into the root of the project.
And run...

```
NODE_ENV=production node server.js
```

Check in browser on [http://localhost:5000/](http://localhost:5000/)

## Preview

![Annotation 2020-06-22 055928 (2)](https://user-images.githubusercontent.com/39223762/87814977-0e932d80-c865-11ea-9dde-d60ed8b3c067.png)
![image](https://user-images.githubusercontent.com/69083192/122090092-0781f000-ce25-11eb-9a0c-1c363d730bdf.png)
![image](https://user-images.githubusercontent.com/69083192/122090314-44e67d80-ce25-11eb-8d05-3760de1c44a0.png)

## App Info

## Author

Prince0047
