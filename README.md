### Discord Experiments™

#

### Code to unlock Discord Experiments!
### This Was Created by [ItzNexus](https://youtube.com/ItzNexus)

#

### Set it up EASILY!
![How to do it?](https://user-images.githubusercontent.com/89626058/139572505-e300e142-fe2e-47f6-ab78-7913b54b44f4.png)

## You can unlock discord experiments tab in a few steps.
### STEP 1: Go to Discord (browser)

#

### STEP 2: Press "Ctrl+Shift+i"

#

### STEP 3: Go to "Console" tab and paste this code in:

```js
// CODE BY ITZNEXUS
let wpRequire;
window.webpackChunkdiscord_app.push([[ Math.random() ], {}, (req) => { wpRequire = req; }]);
mod = Object.values(wpRequire.c).find(x => typeof x?.exports?.default?.isDeveloper !== "undefined")
usermod = Object.values(wpRequire.c).find(x => x?.exports?.default?.getUsers)
nodes = Object.values(mod.exports.default._dispatcher._actionHandlers._dependencyGraph.nodes)
try {
    nodes.find(x => x.name == "ExperimentStore").actionHandler["CONNECTION_OPEN"]({user: {flags: 1}, type: "CONNECTION_OPEN"})
} catch (e) {}
oldGetUser = usermod.exports.default.__proto__.getCurrentUser;
usermod.exports.default.__proto__.getCurrentUser = () => ({hasFlag: () => true})
nodes.find(x => x.name == "DeveloperExperimentStore").actionHandler["CONNECTION_OPEN"]()
usermod.exports.default.__proto__.getCurrentUser = oldGetUser
// CODE BY ITZNEXUS
```

#

### STEP 5: Click Enter and you're done!

#

### Socials
[<img align="left" alt="ItzSidhan | YouTube" width="22px" src="https://cdn4.iconfinder.com/data/icons/logos-and-brands/512/395_Youtube_logo-128.png" />](https://bit.ly/ItzSidhanYT)
<a href="https://dsc.gg/itzsidhan">
  <img align="left" alt="Discord" width="23px" src="https://raw.githubusercontent.com/peterthehan/peterthehan/master/assets/discord.svg" />
</a>
<a href="https://twitter.com/ItzSidhan">
  <img align="left" alt="Twitter" width="23px" src="https://raw.githubusercontent.com/peterthehan/peterthehan/master/assets/twitter.svg" />
</a>
