# vue-lib-template
🛠 Simple template for building and publishing component/library to [NPM](https://www.npmjs.com/), Base on [webpack-simple](https://github.com/vuejs-templates/webpack-simple) & [bili](https://github.com/egoist/bili)

# 💻 Usage

- Install [vue-cli](https://github.com/vuejs/vue-cli)
``` bash
$ npm install -g vue-cli 
```

- Initial component/library
``` bash
$ vue init biigpongsatorn/vue-lib-template my-project
$ cd my-project
$ npm install
$ npm run dev
```

# 🗂 Directory Structure

```
my-project
│
├── demo
│   ├── App.vue
│   └── main.js
├── src
│   └── index.vue
├── .babelrc
├── .editorconfig
├── .gitignore
├── .npmignore
├── bili.config.js
├── index.html
├── package.json
├── README.md
└── webpack.config.js
```

# 🏛 Building
- Building demo page.
``` bash
$ npm run build:demo
```

- Building component/library.
``` bash
$ npm run build:lib
```

- Publishing to npm.
``` bash
$ npm publish
```

# 🙏🏻 Support

```
If you like this project, You can support me with starring ⭐ this repository.
```

# 🖊 License

[MIT](LICENSE)

Developed with ❤️ and ☕️ 