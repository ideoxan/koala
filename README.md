<p align="center"><img src="https://raw.githubusercontent.com/ideoxan/koala/master/koala.png"></p>
<p align="center">🖥️ Koala is a web-based, open source code editor for the Ideoxan Website.</p>

## About
This repository features the OSS version of the Koala editor that is used on the Ideoxan Website for lesson completion and course activities. Often times, the phrases "Ideoxan Editor" and "Koala" are used interchangeably. Koala is simply just a nickname/code word for the Ideoxan editor and is only used for this repository.

<img width="50%" height="50%" align="right" src="https://raw.githubusercontent.com/ideoxan/ideoxan/master/content/www/static/img/webdrop.png">

The editor has many features, yet its light and simple. It has a tabbed interface at the top for all of the files which are held virtually within the memory. It also contains a customizable viewport that can be used to display a terminal, a website, or anything else. The lesson guide is simply a markdown document that is loaded from the course that displays helpful information needed to complete lessons. At the bottom of this lesson guide is where the lesson tasks are located.

Every part of the editor is connected to one another. For example, the tasks section in the lesson guide is updated whenever both the viewport and the code are updated.

Internally, Koala uses the [Ace Editor](https://ace.c9.io/) to power the code editor. From there, multiple other libraries are used for rendering the viewport, rendering the lesson guides, saving the data to your accounts, and completing a course.

## Release schedule
The release schedule for Koala is simple. The `main` branch is considered the bleeding edge of the release cycle and includes all changes to the codebase. These changes are then individually reviewed and pushed to the `prod` branch every month which is then synced with the [main repository](https://github.com/ideoxan/ideoxan).

## Running
In it's current state, the editor can not be run as a standalone program or website. It relies on input from the server, and therefore can not run without it. If you'd like to run the editor, visit the [main repo](https://github.com/ideoxan/ideoxan).

*However, if you'd like to try and port this to electron/nwjs, you are more than welcome to open a PR or contact us*
## Contributing
If you would like to contribute to this project, please read the [Contributing Guidelines](https://github.com/ideoxan/contributing)!

## License and Community
While this repository as a whole is licensed under the [MIT License](LICENSE), keep in mind that this does not mean that *all* content is under said license. Certain documents and media included or referenced to may be licensed differently, restricted/copyrighted, or may not be licensed at all.

This project is maintained and governed in accordance with the project's official [Code of Conduct](https://github.com/ideoxan/contributing/blob/main/CODE_OF_CONDUCT.md). Agreement to its terms and conditions, along with [Ideoxan's Official Terms of Service](https://ideoxan.com/tos), [Ideoxan's Privacy Policy](https://ideoxan.com/privacy) and the included [license (MIT)](LICENSE) is *required* to contribute to this organization's project.

<br>
<h3 align="center">Get In Touch With Us!</h3>
<p align="center">
    <a href="https://ideoxan.com"><img src="https://img.shields.io/badge/Ideoxan%20Website%20-%23804DDE?style=for-the-badge"></a>
    <a href="https://github.com/ideoxan"><img src="https://img.shields.io/badge/Github%20-%23181717?style=for-the-badge&logo=github&logoColor=white"></a>
    <a href="mailto:hello@ideoxan.com"><img src="https://img.shields.io/badge/EMail%20Us%20-%23121212?style=for-the-badge"></a>
    <a href="https://discord.gg/jxqKy6r"><img src="https://img.shields.io/discord/717471253753102470?color=%237289DA&label=Discord&logo=discord&logoColor=white&style=for-the-badge"></a>
</p>
