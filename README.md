# Inquirer Corrections
A command-line Node.js tool for collecting JSON data corrections from a user. Inquirer is the application's primary dependency.

*NB*: This tool is not complete. It should run and complete some of its tasks, but others will break or simply not work.

## Prerequisites
- [Node.js/npm](https://nodejs.org/en/download/)

## Getting Started
- Run `git clone https://github.com/mchlltt/inquirer-corrections.git` or `git clone git@github.com:mchlltt/inquirer-corrections.git` to clone the repository.
- Run `npm install` to install Inquirer and its dependencies.
- Follow the data preparation instructions below.
- Run `node app.js`.

## Data preparation
- Fill out and remove the `-template` from `corrections-template.json` before use. `corrections.json` is included in the `.gitignore`.
- If you would like to demo the app's functionality with synthetic data, the program will default to using the data in `data/`.
- If you would like to use your own data, fill out and remove the `-template` from `paths-template.js` before use. `paths.js` is included in the `.gitignore`.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details 

## Author
Mich Elliott - [mchlltt](http://github.com/mchlltt)

## Built With
- [JetBrains WebStorm](https://www.jetbrains.com/webstorm/)
- [Inquirer.js](https://github.com/SBoudrias/Inquirer.js/)

## Acknowledgements
My time working on this project is funded by Northwestern University's [Institute for Sexual and Gender Minority Health and Wellbeing](http://isgmh.northwestern.edu/). Visit the RADAR Project's [DokuWiki Codebook](http://codebook.netcanvas-r.com/doku.php?id=radar:start) if you are interested in the study collecting the kind of data shown in the synthetic data.
