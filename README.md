<!-- Please do not edit this file. Edit the `blah` field in the `package.json` instead. If in doubt, open an issue. -->


















# bloggify-plugin-loader

 [![Version](https://img.shields.io/npm/v/bloggify-plugin-loader.svg)](https://www.npmjs.com/package/bloggify-plugin-loader) [![Downloads](https://img.shields.io/npm/dt/bloggify-plugin-loader.svg)](https://www.npmjs.com/package/bloggify-plugin-loader)







> The Bloggify plugin loader.






This is the default plugin loader for Bloggify.












## :cloud: Installation

```sh
# Using npm
npm install --save bloggify-plugin-loader

# Using yarn
yarn add bloggify-plugin-loader
```






















## :question: Get Help

There are few ways to get help:



 1. Please [post questions on Stack Overflow](https://stackoverflow.com/questions/ask). You can open issues with questions, as long you add a link to your Stack Overflow question.
 2. For bug reports and feature requests, open issues. :bug:





## :memo: Documentation


### `bloggifyPluginLoader(bloggify)`
BloggifyPluginLoader
The Bloggify plugin loader.

#### Params

- **BloggifyCore** `bloggify`: The `BloggifyCore` instance.

#### Return
- **BloggifyPluginLoader** The `BloggifyPluginLoader` instance.

### `getPluginPath(pluginName)`
Fetches the plugin's path.

#### Params

- **BloggifyPlugin** `pluginName`: The plugin's name.

#### Return
- **String** The plugin's path.

### `namesToPaths(names)`
Fetches the path list for each plugin.

#### Params

- **Array** `names`: The list of plugin names.

#### Return
- **Array** The path list.

### `listPluginDirs(names, cb)`
Fetches the list of the plugin's instances.

#### Params

- **Array** `names`: The list of plugin names.
- **Function** `cb`: The callback function.

### `getPlugin(plugin)`
Fetches called plugin's content if it's valid. Otherwise, it fetches a new one.

#### Params

- **BloggifyPlugin** `plugin`: The plugin's name.

#### Return
- **BloggifyPlugin|String** The plugin's name or instance.

### `listPlugins(names, cb)`
Fetches the plugins list.

#### Params

- **Array** `names`: The list of plugin names.
- **Function** `cb`: The callback function.

### `initPlugin(plug, cb)`
Initializes the plugin's instance.

#### Params

- **BloggifyPlugin** `plug`: The plugin instance.
- **Function** `cb`: The callback function.

### `loadAll(names, cb)`
Initializes the plugins that need to be loaded.

#### Params

- **Array** `names`: The list of plugin names.
- **Function** `cb`: The callback function.

#### Return
- **Promise** A promise.

### `loadPlugin(plugin, cb)`
Loads the provided plugin.

#### Params

- **BloggifyPlugin** `plugin`: The plugin instance.
- **Function** `cb`: The callback function.

### `get(name, mod)`
If `true`, the raw plugin module will be returned. Otherwise, it will fetch the instance of the plugin.

#### Params

- **String** `name`: The plugin's name.
- **Boolean** `mod`: The plugin's module. Default: `true`

#### Return
- **BloggifyPlugin|String** The plugin's name or instance.














## :yum: How to contribute
Have an idea? Found a bug? See [how to contribute][contributing].
















## :dizzy: Where is this library used?
If you are using this library in one of your projects, add it in this list. :sparkles:

 - `bloggify`











## :scroll: License

[MIT][license] © [Bloggify][website]






[license]: /LICENSE
[website]: https://bloggify.org
[contributing]: /CONTRIBUTING.md
[docs]: /DOCUMENTATION.md
