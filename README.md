# Web Based Nodejs - Login System
- Thanks to C WebDevSimplified

#### However, a few things if you are running this in 2023-2024 or later.
- **You must update express module**
- **You have to update package-lock.json**
- **Make sure your sent environment in .env is same as in server.js in app.use**

```
app.use(session({
  secret: process.env.SESSION_SECRET,
  resave: false,
  saveUninitialized: false
}))
```

- With the right dependencies, your application should run.

<img width="946" alt="image" src="https://github.com/WebDevSimplified/Nodejs-Passport-Login/assets/55284959/931f2cfd-a5e4-48b5-bac3-b9da519d860f">
