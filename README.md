# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
export default {
  // other rules...
  parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
  },
}
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list

---Dependencies:

### Routing
npm i react-router-dom

### Style
Bootstrap: npm i bootstrap react-bootstrap

### Credits
Foto di <a href="https://unsplash.com/it/@rodreis?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Rodrigo dos Reis</a> su <a href="https://unsplash.com/it/foto/frutta-gialla-della-banana-sul-tavolo-di-legno-marrone-DkTuGvgPotA?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Unsplash</a>
Foto di <a href="https://unsplash.com/it/@karishea?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Kari Shea</a> su <a href="https://unsplash.com/it/foto/macbook-pro-sopra-il-tavolo-marrone-1SAnrIxw5OY?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Unsplash</a>
Foto di <a href="https://unsplash.com/it/@impatrickt?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Patrick Tomasso</a> su <a href="https://unsplash.com/it/foto/lotto-a-libro-aperto-Oaqk7qqNh_c?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Unsplash</a>
Foto di <a href="https://unsplash.com/it/@danielcgold?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Dan Gold</a> su <a href="https://unsplash.com/it/foto/fotografia-a-fuoco-superficiale-di-volkswagen-beetle-arancione-N7RiDzfF2iw?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Unsplash</a>
  
### Credits for exercise
How To Create An Advanced Shopping Cart With React and TypeScript - https://www.youtube.com/watch?v=lATafp15HWA