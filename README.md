# Meteor Todos, React Native Style

A demo of React Native interacting with a Meteor backend. The goal of this project is to match the feature set of the web version of Meteor's Todos example.

**Note:** Still a work in progress.

## Installation

1. [Install Meteor](https://www.meteor.com/install)
2. [Install React Native](https://facebook.github.io/react-native/docs/getting-started.html) (Only works on OSX currently)

## Running

You'll need two terminal windows to run this example.

1. In terminal window 1 run `cd meteor-todos/ && meteor`
2. In terminal window 2 run `cd ReactNativeTodos/ && npm install && npm run app`
3. After the npm dependencies are installed Xcode should open. You can then press the play button in the top left of Xcode and the iOS simulator should open.

## Changes made to the Meteor Todos Example

I wanted to minimize the number of changes I made to the example provided by Meteor (created by running `meteor create --example todos`). The only addition I made was adding a few Meteor methods in `meteor-todos/lib/methods.js`.
