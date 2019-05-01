Wagerr Electron App
===================

A modern cross-platform GUI for Wagerr built with [Electron](https://electronjs.org/) & [Vue.js](https://vuejs.org/).

Prerequisites
-------------

Make sure you back up your Wagerr wallet.dat before running this wallet.

You need the following prerequisites to be able to build and develop the
project on your local machine.

**NodeJS + NPM**

Install the latest version of NodeJS and NPM for your OS using the link below:

```
https://nodejs.org
```

Once installed test it by opening a terminal on your local computer and enter the following command:

```
node -v
```

```
npm -v
```

If installed correctly you will see the current version your are running for NodeJS and NPM.

**Get the source**

```
git clone https://github.com/wagerr/wagerr-electron-app.git
```

Change directory into the newly cloned repository:

```
cd wagerr-electron-app
```

**Wagerr binaries**

Make a `bin` directory in the root of the repo and place `wagerrd` and
`wagerr-cli` binaries in this directory.

**Install dependencies**

```
npm install
```

Run the application
-------------------

Run in development mode:

```
npm run dev
```

To build (don't forget to have the Wagerr binaries available in the `bin` dir):

```
npm run build
```

After running the build command the executable will be located in the `release`
folder.

Built With
----------

- [Node.js](https://nodejs.org/)

- [Electron](https://electronjs.org/)

- [Vue.js](https://vuejs.org/)

Contributing
------------

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of
conduct, and the process for submitting pull requests to us.

License
-------

Licensed under the [MIT](LICENSE.md) License.
