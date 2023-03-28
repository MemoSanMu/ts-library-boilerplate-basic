 <div align="center">
 <img align="center" width="230" src="https://i.imgur.com/iHgtvmg.png" />
  <h2>Typescript Library Boilerplate Basic</h2>
  <blockquote>Minimal Library Starter Kit for your Typescript projects</blockquote>

## 💎 Customization

> Before shipping, make sure to:

1. Edit `LICENSE` file
2. Edit `package.json` information (These will be used to generate the headers for your built files)
3. Edit `library: "MyLibrary"` with your library's export name in `./webpack.config.js`

## 🚀 Deployment

1. `npm publish`
2. Your users can include your library as usual

### npm

```
import MyLibrary from 'my-library';
const libraryInstance = new MyLibrary();
...
```

### self-host/cdn

```
<script src="build/index.js"></script>

const MyLibrary = window.MyLibrary.default;
const libraryInstance = new MyLibrary();
...
```

## ✅ Libraries built with this boilerplate

> Made a library using this starter kit? Share it here by [模版来源](https://github.com/hodgef/ts-library-boilerplate-basic)!

- [simple-keyboard](https://github.com/hodgef/simple-keyboard) - Javascript Virtual Keyboard
- [react-simple-keyboard](https://github.com/hodgef/react-simple-keyboard) - React Virtual Keyboard
- [simple-keyboard-layouts](https://github.com/hodgef/simple-keyboard-layouts) - Keyboard layouts for simple-keyboard
- [atlas-monaco](https://github.com/datdao/atlas-monaco) - AtlasHCL for monaco editor
