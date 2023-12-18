# Web Based Nodejs Passport Login System 
- Thanks to C WebDevSimplified - This is one of the most helpful opensource Projects for WebDevs.

#### However, a few things if you are running this in 2023-2024 or later.
- **You must update express module**
- **You have to update package-lock.json**

```
npm i --package-lock-only
```

or via yarn

```
yarn install --mode update-lockfile
```
- **Make sure your set environment in .env is correspond to your key in server.js in app.use**

```
app.use(session({
  secret: process.env.SESSION_SECRET,
  resave: false,
  saveUninitialized: false
}))
```

- With the right dependencies, your application should run.

<img width="946" alt="image" src="https://github.com/WebDevSimplified/Nodejs-Passport-Login/assets/55284959/931f2cfd-a5e4-48b5-bac3-b9da519d860f">


