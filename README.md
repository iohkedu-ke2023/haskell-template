# Template to start your own Haskell project

The code itself is nothing more than what you get when doing `cabal init`. The purpose of this template is to provide the development environment on top. This consists of:

- `ghcup`: The main installer for Haskell.
- `ghc` (the Haskell compiler) version 9.2.5.
- `cabal-install` and Cabal library (a build tool for Haskell) version 3.6.2.0.
- `haskell-language-server` version 1.9.1.0
- `stylish-haskell` formatter.

You have two ways of using this development environment (If you already have the previous tools installed in your system, you can ignore this):

- To have a remote development environment: [Install the GitPod extension](https://www.gitpod.io/docs/configure/user-settings/browser-extension), and click the new "Gitpod" button at the top of the repo.
- To have a local development environment inside Docker: Make sure you have the latest version of [Docker Desktop](https://www.docker.com/products/docker-desktop/) and [VSCode](https://code.visualstudio.com/). Open the `examples-haskell` folder in VSCode (not the repo's root). You'll get a notification about a Dev Container config file. Click on "Reopen in Container." Alternatively, you can do this with a blank repo. To start fresh.

Alternatively, if you prefer to install directly on your hardware:

- To get your local development environment directly on your computer using GHCup: Follow [these instructions](https://www.youtube.com/watch?v=hSN5mxITv0A&list=PLNEK_Ejlx3x1D9Vq5kqeC3ZDEP7in4dqb&index=13) (all platforms).