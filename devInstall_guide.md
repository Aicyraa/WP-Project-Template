# Configs - (Commands and Configuraiton File)
### Dev Dependencies
```bash
    #dev building
    webpack serve --open --config webpack.dev.js 

    # project bundiling
    webpack --config wenpack.prod.js 

    # Deploying
    git subtree push --prefix dist origin gh-pages
```
### ESlint
```bash
    # To initialize a linting configuration
    npm init @eslint/config@latest

    # use `eslint-config-xo` shared config - npm 7+ (Optional)
    npm init @eslint/config@latest -- --config eslint-config-xo
```
[ESLint Website - Getting Started][1]

### Prettier
```bash
    # creates an empty config file
    node --eval "fs.writeFileSync('.prettierrc','{}\n')"

    # create a prettierigonore to prevent formating unwanted files
    node --eval "fs.writeFileSync('.prettierignore','# Ignore artifacts:\nbuild\ncoverage\n')"

```
[Prettier - Getting Started][2]

[1]: https://eslint.org/docs/latest/use/getting-started
[2]: https://prettier.io/docs/install.html
