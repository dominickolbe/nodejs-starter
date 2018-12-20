# nodejs-starter
> This is a starter nodejs project. It includes babel to use new ES6 features and has some presettings to work with .env ...

## Requirements

### node version manager

I prefer to use [node version manager](https://github.com/creationix/nvm) to manage different versions of nodejs on your computer
```
$ curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.11/install.sh | bash
$ nvm install 9.11
$ nvm use 9.11
```

### env
create .env file based on the example env

```bash
cp .env.example .env
```

## Development
```bash
yarn start

// or with nodemon
nodemon
```

## Build
```bash
yarn build
```

---

Copyright (c) 2018 [Dominic Kolbe](https://dominickolbe.dk)
