# SysDate Component #

This project is a blueprint for creating react controls. It also illustrates how to publish them in git for later installation via npm.

## Repository Info ##

1. Repository Name: rafael-castlebreck
2. Email: rafael.castlebreck@gmail.com
3. Repo: https://github.com/

## Installation ##

You can use npm fetch the package from or, alternatively, manually the component url in package.json

I) Directly from Repository:

```
npm install "git+https://github.com/rafael-castlebreck/sysdate-component-dev.git"
```

II) Manually added in package.json

```
  "dependencies": {
    ...
    "sysdate-component": "git+https://github.com/rafael-castlebreck/sysdate-component-dev.git"
  },
```

## Usage ##

A simple example will be enough to grab the idea.

```
import  SysDate  from 'sysdate-component';

function App() {
  return (
    <div className="App">
      <header className="App-header">
        <SysDate/>
      </header>
    </div>
  );
}

```
