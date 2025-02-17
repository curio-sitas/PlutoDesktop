# Contribution Guidelines
This project is linked to the [Pluto.jl project](https://github.com/fonsp/Pluto.jl), please refer to its [contribution guidelines](https://github.com/fonsp/Pluto.jl/blob/main/CONTRIBUTING.md) as well.

## Prequisites
- Download and install [NodeJS](https://nodejs.org/en/) from [here](https://nodejs.org/en/download/).
- Download latest Julia for Windows 64bit portable from [here](https://julialang.org/downloads/) and put in the assets folder.
- Currently we only support systems running Windows OS.

## Development setup
Just a couple of steps!
- Fork this repo
- Create your branch with appropriate name (Ex. feat/win32-support)
- Clone it to your machine
- cd into the folder
- run `npm install`
- run `npm run start`
> Node: Currently the code has some Windows specific parts, like checking for admin rights etc.

## How to build?
A few things to consider:
- NodeJS and npm should be present on your computer
- There should be a julia-{some version}.zip file in the assets folder when you try to build it

Try running `build.sh` or `build.ps1` present in this repo, or do `npm i` and then `npm run package`. Either of those options should provide you with an installer execuatble in release/build folder.

## Contributing
See if there already exists and issue or an open PR against the issue you are trying to solve. If there isn't any, create a new issue.
