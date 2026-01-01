# Project Title

https://rs3.me website
https://randttech.com

## Description

A personal website highlighting the professional Richard Staehler III

## Getting Started

### Dependencies

The website is currently hosted on Firebase within Google Cloud infrastruture. It is deployed via Jenkins.

Local
* Modern IDE (Visual Studio Code, PyCharm, etc)
* Node JS 24.12+
* firebase-tools

Remote (Jenkins)
* Jenkins (latest version preferred)
* Node JS 24.12+ (installed as a Global Tool)
* firebase-tools (installed as a Global npm within the NodeJS setup)

### Deploying

Deploy locally
* Clone repo `git clone https://github.com/swerenfl/www-rs3`
* Run `firebase init` and follow prompts
    * NOTE: Must be able to authenicate to the project in Firebase
* Make changes and save locally
* Run `firebase deploy`

Deploy via Jenkins
* Clone repo `git clone https://github.com/swerenfl/www-rs3` locally
* Make changes and commit code to the remote repository
* Jenkins will pick up the change via webhook and automatically deploy

## FAQ

Who is Richard Staehler III?
* Here is where you can read all about him. Send him an email if you have additional questions or comments.

What if I want to learn more about Richard Staehler III?
* Drop Richard an email. His email can be found within the site.

What does Richard Staehler III do for fun?
* This is all detailed on the site

## Authors

Richard Staehler III  

## Version History

* 2026.1.1 (main)
    * Updated copyright date to be automatic instead of static
    * Updated Firebase Tokens for GOOGLE_APPLICATION_CREDENTIALS
* ... (main)
    * Various updates throughout time
* 2020.2 (main)
    * Various alignment issues, optimizations, unfurling
    * Added images including favicon
    * See [commit change](https://github.com/swerenfl/www-rs3/commits/main) for further changes
* 2020.1 (main)
    * Initial Release

## License

This project is licensed under the CCA 3.0 license (html5up.net/license) License - see the LICENSE.txt file for details

## Acknowledgments

Design, images, etc.
* [Aerial by HTML5 UP](https://html5up.net)
* [Firebase](https://firebase.google.com/docs/hosting)
* [Jenkins](https://www.jenkins.io/)