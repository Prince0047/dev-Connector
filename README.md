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

### Login/Signup
![image](https://user-images.githubusercontent.com/69083192/138848885-6d139a14-6eaf-47ae-94fa-af199a4b66f4.png)
![image](https://user-images.githubusercontent.com/69083192/138848953-790f9f89-adcc-45b1-b6b4-c86bc7656a87.png)

### Developers
![image](https://user-images.githubusercontent.com/69083192/138847435-98bf8c1c-3cab-48fa-bfca-2c07a3e9e20f.png)

### Profile
![image](https://user-images.githubusercontent.com/69083192/138847683-e7724d1e-16d8-4611-8b23-a77428a67719.png)
![image](https://user-images.githubusercontent.com/69083192/138847873-b0bf8ae5-f25f-4821-9258-30438e927c15.png)

### Posts
![image](https://user-images.githubusercontent.com/69083192/138848056-558e64c8-2159-4120-a634-2a7f56fcb2f8.png)

### Group
![image](https://user-images.githubusercontent.com/69083192/138848518-5fd5832f-d340-4580-bf2e-f74871852de3.png)

## App Info

## Author

Prince0047
