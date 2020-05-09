# Installation

## windows users

Please skip **step 1** if you already have node installed.

#### step 1: install node and npm

- Go to https://nodejs.org/en/ to install node

#### step 2: install gitbash

- Go to https://gitforwindows.org/ to install Git Bash

#### step 3: install VS Code (_optional_)

We recommend you use [VS Code](https://code.visualstudio.com) as coding environment and again _"you don't have to if you don't like it."_
If you have it or you do like to use it, however, I recommend you install the following VS Code extensions for better experience. (these extensions have nothing to do with the app at all, they are just good for coding experience in VS Code IDE)

- Atom keymap (by Microsoft)
- bookmarks (by Alessandro Fragnani)
- Bracket Pair Colorizer (by CoenraadS)
- ES7 React/Redux/GraphQL/React-Native snippets (by dsznajder)
- import cost (by Wix)

#### Step 3: Install expo-cli

```
npm install expo-cli --global
```

#### Step 5: Install the dependencies and devDependencies.

```sh
$ cd [APP_FOLDER]
```

Then run:

```sh
$ yarn install
$ yarn start
```

OR

```sh
$ npm install
$ npm start
```

#### Step 4: Test the app

Test the app on your real device by following the instructions by scanning the QR code.

## macOS users

Please skip **step 1** and **step 2** if you already have node installed.

#### Step 1: Install Homebrew

Homebrew is "The missing package manager for macOS".
Open terminal and type the following command.

```
$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

this will install Homebrew on your Mac. To check the version type the following command.

```
$ brew -v
```

#### Step 2: Install Node via Homebrew

In the terminal type the following command to install Node.

```
$ brew install node
```

If everything installed successfully then you can type in the following command in the terminal to check the Node and NPM version.

```
$ node -v
$ npm -v
```

#### Step 3: Install expo-cli

```
npm install expo-cli --global
```

#### Step 5: Install the dependencies and devDependencies.

```sh
$ cd [APP_FOLDER]
```

Then run:

```sh
$ yarn install
$ yarn start
```

OR

```sh
$ npm install
$ npm start
```

#### Step 4: Test the app

Test the app on your real device by following the instructions by scanning the QR code.
