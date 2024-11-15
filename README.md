![Build badge](https://sfa-gov-uk.visualstudio.com/_apis/public/build/definitions/c39e0c0b-7aff-4606-b160-3566f3bbce23/788/badge)

# Apprentice App iOS Android



## License

Licensed under the [MIT license](LICENSE)



This project uses Bubblewrap to package the My Apprenticeship (Progressive Web App) for delivery via Google's Play store. 


Setup


Full Bubblewrap set-up instructions can be found here: https://github.com/GoogleChromeLabs/bubblewrap/tree/main/packages/cli

## as of 01/11/2024 Bubblewrap or rather one of the libraries or tools it depends on has issues with the latest version (v22) of node therefore it is recommended to downgrade to an earlier version.

Setting up the Environment
When running Bubblewrap for the first time, it will offer to automatically download and install external dependencies. This is the recommended setup, but it's possible to manually setup the environment.

Container
As an alternative to running the cli on your machine with Node.js directly you can use this container image which got the cli and all dependencies pre-installed. To use the cli run docker run --rm -ti ghcr.io/googlechromelabs/bubblewrap:latest [cmd] as you would normally use bubblewrap [cmd].

Quickstart Guide
Installing Bubblewrap
npm i -g @bubblewrap/cli


Build Instructions

run Bubblewrap build