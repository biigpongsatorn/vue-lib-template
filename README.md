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

# 🤝 Contributing
1. Fork this repository.
2. Create new branch with feature name.
3. Run `npm install` and `npm run dev`.
4. Create your feature.
5. Commit and set commit message with feature name.
6. Push your code to your fork repository.
7. Create pull request. 🙂

# 🙏🏻 Support

```
If you like this project, You can support me with starring ⭐ this repository.
```

# 🖊 License

[MIT](LICENSE)

Developed with ❤️ and ☕️ 