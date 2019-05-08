# surfloat
## Landing page built with advanced CSS

This project uses:
- A custom grid with float layout
- A SASS architecture (7-1 pattern, BEM standard)
- CSS animations
- CSS popup
- Icon fonts
- A desktop first responsive design: images (art direction, density switching, resolution switching), prefixes for browsers supports
- Npm scripts to compile and watch for changes automatically
---
To see a demo of the angular version: https://surfloat.herokuapp.com/
- *NB: It can take up to 1 minute for the server to charge*

# cmd for static version

## Development mode

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

Finally go to http://127.0.0.1:8080/

## Deployment mode

Comment icon font basic stylesheet in index.html since it's already compiled in package.json:
```
<!-- <link rel="stylesheet" href="css/icon-font-basic.css"> -->
```

Compile the project:
```
npm run build:css
```
