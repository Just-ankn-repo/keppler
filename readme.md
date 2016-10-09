# Keppler

An efficient way to share your code while presenting

### What is keppler

Keppler lets you share your code during a presentation.

Start keppler inside your project folder, share the URL with the viewers and start coding. When you save or change any files, viewers receive them, can browse through the files tree and discover changes you've made.

Keppler is easy to install and works with NodeJS.

![Project screen](https://github.com/brunosimon/keppler/raw/master/resources/screenshots/screen-project-1.png)

### Instructions

**Requirements**
* [NodeJS](https://nodejs.org/en/) installed
* Keppler installed globally
* Viewer connected to the same network

**Install Keppler globally**

```
npm install -g keppler
```

**Start Keppler inside the project folder**

```
cd ./my-awesome-project
keppler "My project"
```

Share the URL that should appear with the viewers.

### TODO
- [ ] Log project URL and open in default browser
- [ ] Fix debug in packaged version
- [x] Lastest version on top
- [ ] Copy file to clipboard button
- [ ] Download file button
- [ ] Font size buttons

### Futur features

- 404
- Config file
- Keyboard navigation
- In app notifications
- Navigator notifications
- Toggle folder
- Retractable sidebar
- File searching/filtering
- Project history
- Tooltips
- Open multiple files
- Unit testing
- Tablet compatible
- Angular 2
- Font-size control
- Theme control
