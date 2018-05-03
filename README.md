## koa-starter

### What includes:

* Multipy use of Koa-Routers
* Flowtype
* ESLint
* Backpack

### Usage

### Clone:

```bash
git clone https://github.com/vamosgs/koa-starter.git
```

### Environment:

    Change .envEXAMPLE to .env for starting develompent.

### Routing:

Create your router in src/routes folder
then import it in src/routes/index.js

example:

```js
const newRouter = require("./newRouter");

const routes = combineRouters([root, newRouter]);
```

### Commands:

* Build:
  ```bash
  yarn build
  ```
* Dev server:

  ```bash
  yarn dev
  ```

* Start on your server:

  ```bash
  yarn start
  ```

### WIP...