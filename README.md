# TodoMVC with OrbitDB

> Serverless and collaborative Todo lists

TodoMVC application using [OrbitDB](https://github.com/orbitdb/orbit-db) as a database for the todo list and [IPFS](https://github.com/ipfs/js-ipfs) as the storage and networking. This is an example to demonstrate how OrbitDB enables multi-user, real-time and serverless editing of a dataset.

***Work in progress***

**[LIVE DEMO](https://ipfs.io/ipfs/QmTJGHccriUtq3qf3bvAQUcDUHnBbHNJG2x2FYwYUecN43/)**

<p align="centers">
  <img src="https://raw.githubusercontent.com/haadcode/example-orbitdb-todomvc/master/screenshots/Screen%20Shot%202017-11-29%20at%2017.09.31.png" width="50%">
</p>

## Install
```
git clone <repo>
cd repo/
npm install
npm run build
```

## Run
```
npm start
```

Open your browser at http://127.0.0.1:8080

## Collaborative editing by multiple users

To collaborate on a TODO list, open the same url in *another browser or incognito window*. You should see the TODO lists sync automatically.

## More Info

This example is based on [React TodoMVC](https://github.com/tastejs/todomvc/tree/master/examples/react).

- Initializing OrbitDB and IPFS happens in [store](https://github.com/haadcode/example-orbitdb-todomvc/blob/master/src/store.js)
- OrbitDB calls happen in [model](https://github.com/haadcode/example-orbitdb-todomvc/blob/master/src/todoModel.js)
- The database and app are hooked together in [app](https://github.com/haadcode/example-orbitdb-todomvc/blob/master/src/app.jsx#L188)

## Contribute

We'd be happy have contributions! If you find any issues, have suggestions for new features or would like to improve the project, please open an issue.

## License

[MIT](LICENSE) © 2017-2018 Haja Networks Oy
