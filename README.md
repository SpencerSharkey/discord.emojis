you can find json files in dist folder

`npm install @c4t/emojis`

`npm install devcat/discord.emojis#<commit-hash>`

`git submodule add https://github.com/devcat/discord.emojis`

```js
import emojis from '@c4t/emojis';

console.log(emojis.kv);
console.log(emojis.default);
console.log(emojis.metadata);
```
