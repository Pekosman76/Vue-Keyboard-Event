# Project Title

Simple way to get Keyboard Event from vue js project

### Add EventListener for keyboard

When components is lunch, add event that will listen keyboard event (keydown, keypress et keyup are available)

```
mounted () {
  window.addEventListener("keydown", this.getKeyboard);
}
```

### Add Methods for receive event 

Methods that will get keyboard event 

```
methods: {
  getKeyboard: function(event) {
    console.log(event.key)
  }
}
``` 

### KeyboardEvent documentation
https://developer.mozilla.org/fr/docs/Web/API/KeyboardEvent
