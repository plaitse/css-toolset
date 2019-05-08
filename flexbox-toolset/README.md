# surfloat
Landing page built with advanced CSS

This project uses:
- CSS flexbox layout
- SVG CSS image sprites
- SASS architecture
- CSS BEM standard
- CSS animations
- Npm scripts to compile and watch for changes automatically

To see a demo of the angular version: https://surfloat.herokuapp.com/

# cmd for static version

# Development mode

Install live server globally on your machine:
```
 npm install -g live-server
```

Install node modules:
```
 npm install
```

Launch the project:
```
 npm run start
```

Go to http://127.0.0.1:8080/

# Deployment mode

Comment icon font basic stylesheet in index.html since it's already compiled in package.json:
```
<!-- <link rel="stylesheet" href="css/icon-font-basic.css"> -->
```

Compile the project:
```
npm run build:css
```

# TODO
- Create user menu/settings
- Create chat/message dropdown list
- Create autocomplete dropdown list results
- Create title hover effect on images
- Mobile phone responsive