# hydronode
> Modular and universal hydroinformatics & data translations

Hydronode is based on [Bionode](http://bionode.io). 

Like Bionode, Hydronode provides pipeable UNIX command line tools and JavaScript APIs for hydroinformatic analysis, but also has translation workflows at it's heart.

The documentation and setup of Hydronode largely mirrors the structures of Bionode. 

Install
-------

[Install Node.js](http://nodejs.org) (we recommend using [n](https://github.com/tj/n)).

If you want to install hydronode in your current folder and use the **JavaScript API**, do:
```bash
npm install hydronode
```

If you want to install it globally and use it as a **command line tool** add ```-g```, like:
```bash
npm install hydronode -g
```

The previous commands will install all hydronode modules currently available.

If you don't need all modules and prefer to be more selective, have a look at the [list of modules](#list-of-modules).


Usage
-----

If you're using hydronode with Node.js, you can require the module:

```js
var hydronode = require('hydronode')
```

If you're using it as a command line tool, type hydronode \<module\> \<command\> \<arguments\>, e.g.:

```bash
hydronode hydstra search qld site 222901
```

Please read the [documentation](//rawgit.com/hydronode/hydronode/master/docs/hydronode.html) for the methods exposed by hydronode.


List of modules
--------------

The following are modules available/planned for Hydronode.

| Name                   | Type          | Description                                       | Status<sup>1</sup>          | People                                                   |
|------------------------|---------------|---------------------------------------------------|-----------------------------|-----------------------------------------------------------------------|
| [hydstra]              | Parser, Importer, Translater   | Access to [Kisters-Hydstra] water data webservices           | ![development][development]   |   |
| [qldgwdb]              | Parser, Importer, Translater  |  Manual upload of Queensland Government Groundwater Database                                     | ![development][development]      |  |

[1]: Current status of the module
* ![production][production] means the module is still in development but has many features complete and is used intensively. 
* ![development][development] means the module still lacks some features, tests or has some issues.
* ![request][request] means the module has been requested, discussed and planned, but is not yet implemented.

[production]:https://img.shields.io/badge/status-production-green.svg?style=flat-square
[development]:https://img.shields.io/badge/status-development-orange.svg?style=flat-square
[request]:https://img.shields.io/badge/status-request-blue.svg?style=flat-square


Support
-------

If you find a bug please use the [issues](http://github.com/hydronode/hydronode/issues) tracker to report it.  
If you need help with this particular module, you can use the respective [gitter](http://gitter.im/hydronode/hydronode) chat room.  
For general help or discussion about the hydronode project, you can use the IRC channel [#hydronode](https://www.irccloud.com/#!/ircs://irc.freenode.net:6697/%23hydronode) on Freenode.  
Hydronode is collaborating with [BioJS](http:/biojs.net) which also has a IRC channel at [#biojs](https://www.irccloud.com/#!/ircs://irc.freenode.net:6697/%23biojs).


Contributing
------------
Please see [CONTRIBUTING.md](CONTRIBUTING.md) for how to contribute to this project.  
For a list of contributors, see the file [contributors.md](contributors.md).

Contacts
--------
[Sholto Maud](http://sholtomaud.com) <[mail@sholtomaud.com](mailto:sholto.maud@gmail.com)> [@sholtomaud](//twitter.com/sholtomaud)  

License
-------

hydronode is licensed under the [MIT](https://raw.github.com/hydronode/hydronode/master/LICENSE) license.  
Check [ChooseALicense.com](http://choosealicense.com/licenses/mit) for details.
