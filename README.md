# Chromebook Hacks

An updated exploit guide and wiki for a wide variety of chromebook exploits and tools. This website is built using [Docusaurus](https://docusaurus.io/), a modern static website generator.
 
### Installation
 
```
$ npm i
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

Using SSH:
 
```
$ USE_SSH=true yarn deploy
```
 
Not using SSH:
 
```
$ GIT_USER=<Your GitHub username> yarn deploy
```
 
If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.

### Contributors
<a href="https://github.com/chromebook-hacking/chromebook-hacking.github.io/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=chromebook-hacking/chromebook-hacking.github.io" />
</a>

# TODO
- [x] Chooser tool (sorta)
- [ ] Any exploits that haven't been added yet
- [ ] Page edits
- [ ] Grammar and spelling issues
- [ ] More tools (see [ext-remover](https://ext-remover.net) and the [repo](https://github.com/3kh0/ext-remover))
