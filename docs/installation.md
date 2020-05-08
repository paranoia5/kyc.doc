# Installation

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
