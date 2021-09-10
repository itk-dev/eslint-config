# ITK Dev eslint config

## Usage

```sh
npm install --save-dev @itkdev/eslint-config
```

```sh
yarn add --dev @itkdev/eslint-config
```

```sh
cat > .eslintrc.json <<'EOF'
{
    "extends": "@itkdev"
}
EOF
```

<https://eslint.org/docs/developer-guide/shareable-configs>

## Publishing

```sh
npm adduser itkdev
npm version «some version»
npm publish --access public
git push --tags
```
