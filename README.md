# Flowbackweb

The web app for the Flowback platform. 

### Kips Workaround (I don't know react...)

Once the backend is up and running, change the `baseURL` to

```js
baseURL: "http://127.0.0.1:8000"
```

In `App.js`

```
npm start
```

---

I'm not sure what 

```
localStorage.getItem('rootUrl')
```

does, perhaps it gets the env var `rootUrl`? idk. 