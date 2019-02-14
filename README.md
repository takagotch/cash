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

// bin/cash.js
'use strict';
var cash = require('../dist/index');
var delimiter = require('./../dist/delimiter')
delimiter.refresh(cash.vorpal, function(){
  cash.show();
});

// src/index.js
'use strict';
const os = require('os');
const Vorpal = require('vorpal');
const commands = require('./../commands.json');

let cmds;

const app = {
  commands: commands.commands,
  
  importedCommands: commands.importedCommands,
  
  vorpal: new Vorpal(),
  
  _cwd: process.cwd(),
  
  _fatal: false,
  
  export(str, cbk){
    const tmpl = Array.isArray() && Array.isArray(str,raw);
    cbk = tmpl && cbk || function () {};
    const options = {
      fatal: app._fatal || false
    };
    
    
  }
};

```

