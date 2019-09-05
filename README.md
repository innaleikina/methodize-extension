# Methodize Chrome Extension
The goal of this project is to convert the [web browser version](methodize.herokuapp.com) of Methodize to a chrome extesion.  

# To Use
## Add a manifest.json
Add a manifest.json file to the public folder with the following code:
```
{
  "manifest_version": 2,
  "name": "Methodize",
  "author": "Inna Leikian, Lucas Taboada",
  "version": "1.0.1",
  "description": "Organize your thoughts.",
  "icons": {
    "16": "icon16.png",
    "48": "icon48.png",
    "128": "icon128.png"
  },
  "chrome_url_overrides": {
    "newtab": "index.html"
  },
  "permissions": [],
  "content_security_policy": "your script informaiton here"
}
```

# Team Members
[Lucas Taboada](https://github.com/LucasTaboada)
[Inna Leikina](https://github.com/innaleikina)
[Vera Butler](https://github.com/verabutler)

*This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).*
