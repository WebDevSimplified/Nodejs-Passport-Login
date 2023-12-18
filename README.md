# Web Based Nodejs - Login System
- Thanks to WebDev Simplified

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