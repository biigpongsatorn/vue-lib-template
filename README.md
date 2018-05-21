# vue-component-generator
🛠 Vue CLI for generate component/library for building and publishing to npm with [webpack-simple](https://github.com/vuejs-templates/webpack-simple) &amp; [bili](https://github.com/egoist/bili)

# 💻 Usage

- Install [vue-cli](https://github.com/vuejs/vue-cli)
``` bash
$ npm install -g vue-cli 
```

- Generate component/library
``` bash
$ vue init biigpongsatorn/vue-component-generator my-project
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

- Building package.
``` bash
$ npm run build
```

- Publishing package.
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