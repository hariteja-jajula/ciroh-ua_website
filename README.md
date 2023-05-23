# CIROH Documentation Site

This website is built using [Docusaurus](https://docusaurus.io/), a modern static website generator.

## How to Get Started?

1. Clone the repo.
2. Run installation steps from below. 
3. Create new branch for new work in this repo.
4. Update and implement your changes.
5. Push your changes to a branch in this repo.
6. Github actions CI workflow will get triggered automatically.



### Installation

1. Download and Install node js LTS version from https://nodejs.org/en if not already installed.

2. How to build and run this project locally.

``` 
npm install
npm run build
npm run start
```

### Local Development

```
$ npm run start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```
$ npm run build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

To deploy the website, we need to compile this project to deployable package. 

```
$ npm run build
```

above command will create **build** directory in your project folder. We can now deploy the content of that directory to the web server. 


### How do you test build folder locally?

[Reference Article](https://medium.com/swlh/need-a-local-static-server-here-are-several-options-bbbe77e59a11)

we need to run **live-server** inside **build** directory, which let you see how actual published version will look like. 

```
cd into build directory ....
$ npx live-server
```

This should open localhost:8080 with your published site.


-------
using lite-server

```
npx lite-server
```

-------
using http-server

```
npx http-server
```

### Cheatsheet

- [markdown cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- [tina.io](https://tina.io/)
- [Infima](https://infima.dev/docs/getting-started/introduction)

### Contributors
- Arpita Patel (apatel54@ua.edu)
