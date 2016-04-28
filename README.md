# npm-scripts
a collection of scripts that makes my life easier working with node projects

# installation

```bash
$ brew tap doodzik/tap
$ brew install npm-scripts

# add this to your bash/zsh rc file
. n.sh
# or if you dont want nvm to slow down your machine
# run this when you need it
. ninit
```

#### n
npm

#### ni
npm install

#### nis $MODULE_NAMES
installs a list of modules and adds them as a dependencies to the package.json

#### nid $MODULE_NAMES
installs a list of modules and adds them as a devDependencies to the package.json

#### nig $MODULE_NAMES
installs a list of modules as global modules

#### nr $SCRIPT_NAME [$SCRIPT_ARGS]
runs a script with or without arguments that was installed in node_modules/.bin/
i.e. gulp, mocha, ect.

#### ns
npm start

#### nt
npm test
