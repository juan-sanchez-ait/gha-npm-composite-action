# gha-npm-composite-action
This github action is an example of a custom composite action

The action takes as a parameter, the version of node that is required to run "npm ci" & "npm test"

## Inputs
* node-version: The node.js to be used to run the commands.
    * default value: 18