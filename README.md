# VuePress

> WordPress development using Vue, GraphQL, and Express.

## Node Version Requirement

```bash
node 6.*
node 7.*
```

## Config

Using the `/config/sample.config.json` file as an example, create a `development.json` and `production.json` file. The file should contain connection details to your WordPress MySQL database for the respective environments. 

## Build Setup

``` bash
npm install
npm run build
npm start
```

## Development Setup

```bash
npm install
npm run dev
```

## Working With WordPress

### First Steps

In a fresh WordPress install, you'll need to do a few basic setup items:

- Create a page called 'Homepage'
- Create a menu called 'primary-navigation'

### Advanced Custom Fields

VuePress uses some custom post fields. You're best bet is to install the Advanced Custom Fields plugin into your WordPress backend. I've included am `acf-export` JSON file in this repo that you should import. This will give you just a few basic custom page fields that can be used to give your pages custom layout components.

### Layout Components

Currently there are only [two layout components](https://github.com/ramsaylanier/VuePress/tree/master/src/components/page/layouts) - a `DefaultPage` layout and a `PageWithHeader` layout. 

## License

[MIT](http://opensource.org/licenses/MIT)
