## React App Step By Step

```bash
npm init -y
```

```bash
npm install react react-dom react-scripts
```


## Creating index.html in public folder

```html
<!DOCTYPE html
<html>
<head>
  <title>My React App</title>
</head>
<body>
  <div id="root"></div>
</body>
</html>
```

## Creating index.js file in src folder

```javascript
import React from 'react';
import ReactDOM from 'react-dom';
import App from './App';

ReactDOM.render(
  <React.StrictMode>
    <App />
  </React.StrictMode>,
  document.getElementById('root')
);
```