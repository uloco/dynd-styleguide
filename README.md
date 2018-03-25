# dynd-styleguide
Dynamite Dinner Code Styleguide

## Install dependencies

```bash
npm install --save-dev eslint eslint-config-standard eslint-plugin-standard eslint-plugin-promise eslint-plugin-import eslint-plugin-node eslint-config-prettier eslint-plugin-prettier precise-commits husky

npm install --save-dev --save-exact prettier
```

Download `.eslintrc.json` and add it to your project root directory.

## Add to package.json

```json
"scripts": {
	"precommit": "precise-commits"
}
```
