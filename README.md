### cash
---
https://github.com/dthree/cash

```
npm install cash -g
cash

ipconfig | grep IPv4 | sort

npm install cash-global -g
ls -lah

npm install cahs-ls -g
npm install cash-grep -g
```

```js
const $ = require('cash');
const out = $.ls('.', {1: true});

const out = $('ls -lah');

require('cash') `
  cp -R ./src ./dest
  ls | grep *-spec.js | cat
  rm ./specResults.html
`;

$('ls');
$('echo foo > foo.txt');

ls();
echo('foo').to('foo.txt');
```

