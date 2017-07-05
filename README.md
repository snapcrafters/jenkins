<h1 align="center">
  <img src="http://mirrors.jenkins.io/art/jenkins-logo/logo+title.svg" alt="Jenkins" height="256px">
</h1>

<p align="center"><b>This is the snap for Jenkins</b>, the leading open-source automation server. It works on Ubuntu, Fedora, Debian, and other major Linux
distributions.</p>
<p align="center">
<a href="https://build.snapcraft.io/user/snapcrafters/jenkins"><img src="https://build.snapcraft.io/badge/snapcrafters/jenkins.svg" alt="Snap Status"></a>
</p>

## Install

    sudo snap install jenkins
    xdg-open http://localhost:8080

([Don't have snapd installed?](https://snapcraft.io/docs/core/install))

Check the status:

    systemctl status snap.jenkins.jenkins.service

Set a custom configuration:

    cat config.xml | sudo /snap/bin/jenkins.config

<p align="center">Published for <img src="http://anything.codes/slack-emoji-for-techies/emoji/tux.png" align="top" width="24" /> with :gift_heart: by Snapcrafters</p>

## Remaining tasks

Snapcrafters ([join us]()) are working to land snap install documentation and
the [snapcraft.yaml](https://github.com/snapcrafters/discord/blob/master/snap/snapcraft.yaml)
upstream so Discord can authoritatively publish future releases.

  - [x] Fork the [Snapcrafters template]() repository to your own GitHub account
  - [x] Create a snap that runs in `devmode`
  - [x] Register the snap in the store, **using the preferred upstream name**
  - [x] Add a screenshot to this `README.md`
  - [x] Publish the `devmode` snap in the Snap store edge channel
  - [x] Add install instructions to this `README.md`
  - [x] Update snap store metadata, icons and screenshots
  - [x] Convert the snap to `strict` confinement, or `classic` confinement if it qualifies
  - [x] Publish the confined snap in the Snap store beta channel
  - [x] Update the install instructions in this `README.md`
  - [ ] Post a call for testing on the [Snapcraft Forum](https://forum.snapcraft.io) - [link]()
  - [x] Request your GitHub repository is forked to the Snapcrafters organisation and configured for automated builds
  - [x] Add the provided Snapcraft build badge to this `README.md`
  - [x] Publish the snap in the Snap store stable channel
  - [x] Update the install instructions in this `README.md`
  - [ ] Post an announcement in the [Snapcraft Forum](https://forum.snapcraft.io) - [link]()
  - [ ] Submit a pull request or patch upstream that adds snap install documentation - [link]()
  - [ ] Submit a pull request or patch upstream that adds the `snapcraft.yaml` and any required assets/launchers - [link]()
  - If upstream accept the PR:
    - [ ] Request upstream create a Snap store account
    - [ ] Add upstream contact information to the `README.md`
    - [ ] Contact the Snap Advocacy team to request the snap be transferred to upstream
 - [ ] Ask the Snap Advocacy team to celebrate the snap - [link](https://insights.ubuntu.com/2017/05/04/discord-is-now-available-as-a-snap-for-ubuntu-and-other-distributions/)

If you have any questions, [post in the Snapcraft forum](https://forum.snapcraft.io).

## The Snapcrafters

| [![Evan Dandrea](http://gravatar.com/avatar/b9c6dc703231efc4e307d3c59d1f9321?s=128)](https://github.com/evandandrea/) |
| :---: |
| [Evan Dandrea](https://github.com/evandandrea/) |
