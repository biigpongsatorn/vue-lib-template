# vue-lib-template
🛠 A simple template for building and publishing Vue component/library as a opensource, Base on [webpack-simple](https://github.com/vuejs-templates/webpack-simple) & [bili](https://github.com/egoist/bili)

# 💡 Feature
- Light weight template.
- Zero config bundler.
- Quick prototyping.
- This template is Vue 2.0 compatible. 
- Included demo page.

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
├── example
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
$ npm run build:example
```

- Building component/library.
``` bash
$ npm run build:lib
```

- Publishing to npm. (Please run `npm run build:lib` and `npm version patch` before publish to NPM)
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
