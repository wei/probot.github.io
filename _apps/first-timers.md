---
title: First Timers
description: Create starter issues to help onboard new open source contributors
slug: first-timers
screenshots:
  - https://raw.githubusercontent.com/hoodiehq/first-timers-bot/master/assets/Issue-Done.png
authors:
  - agonzalez0515
  - Techforchange
stars: 284
repository: hoodiehq/first-timers-bot
updated: 2025-01-06 08:33:07 UTC
host: https://first-timers-bot.now.sh
organizations:
  - jekyll
  - videojs
  - processing
  - Moya
  - semantic-release
  - hoodiehq
  - skywinder
  - mikaelbr
  - terkelg
  - jeremykenedy
---

# first-timers-bot

### 🐶🎯⛳ The Motivation

From our own experiences, we know the process of creating a pull request is the biggest barrier for new contributors.  We wanted to streamline the process to create very simple contributor-friendly issues to help onboard more people to become Open Source contributors for the first time.

At Hoodie, we aim to become the most [welcoming Open Source community possible](http://hood.ie/blog/welcoming-communities.html). We joined forces with initiatives like [First Timers Only](http://www.firsttimersonly.com/) and [Your First PR](http://yourfirstpr.github.io/) to actively reach out to new contributors and create an environment where they feel encouraged and supported.

Creating what we call [starter issues](http://hood.ie/blog/starter-issues.html) is one aspect of that. And it is one of the most successful. A subset of these starter issues are super simple fixes like typos, so they are perfect to onboard people and help them get familiar with GitHub and the pull request workflow. Because typos and similar issues are so trivial, we should basically be able to automatically generate the entire starter issue based on a diff.

### 💡💥❓ How things work

Say I’m a Hoodie contributor and find a typo somewhere. Instead of fixing the issue directly in the master branch or creating a pull request which is time-consuming, I can simply create a new branch that is called something like _first-timers-typo-in-title._ GitHub will then notify the **First Timers Bot** about the new branch using Webhooks. The bot is listening to any new branch starting with **first-timers** and it will create a new issue on your repo. The commit body can be used to add some context information and if left empty, the 🤔 **What you will need to know** section of the issue will simply say "Nothing :)".


### 😮🙌👀🎉 Use Our Bot!

<table>
    <tr>
        <th>Steps</th>
        <th>Example</th>
    </tr>
    <tr>
        <td>1) <a href="https://github.com/apps/first-timers">Install App</a> on a repo of your choice</td>
        <td><img src="https://raw.githubusercontent.com/hoodiehq/first-timers-bot/master/assets/Install-App.png" alt="Install App"></td>
    </tr>
    <tr>
        <td>2) Click on the file you want to edit.</td>
        <td><img src="https://raw.githubusercontent.com/hoodiehq/first-timers-bot/master/assets/editPic.png" alt="Edit Pic"></td>
    </tr>
    <tr>
        <td>3) Make the change and write your commit message under <b>Commit changes</b>.  Make sure to check <i>Create a new branch</i> at the bottom and the branch needs to start with <b>"first-timers-"</b>.</td>
        <td><img src="https://raw.githubusercontent.com/hoodiehq/first-timers-bot/master/assets/Committing-Branch.png" alt="Committing Branch"></td>
    </tr>
    <tr>
        <td>4) Click on the <b>issues</b> tab and notice your issue was created with your change and commit message. The contributor would then follow the steps on the issue message.</td>
        <td><img src="https://raw.githubusercontent.com/hoodiehq/first-timers-bot/master/assets/Issue-Generated.png" alt="Issue Generated"></td>
    </tr>
</table>

### 😱🙌😎 Result

[Issue Example Here](https://github.com/arlene-perez/bot-app-test/issues/1)

<p align="center"><img src="https://raw.githubusercontent.com/hoodiehq/first-timers-bot/master/assets/Issue-Done.png" alt="Issue Done"></p>

### 👩‍💻💕About Us
<table>
    <col width="200">
    <th>
        <img src="https://avatars.githubusercontent.com/agonzalez0515?s=100" width="100" alt="Angie Gonzalez" style="text-decoration:none"><br><br>
        <a href="https://github.com/agonzalez0515" style="text-decoration:none">Angie Gonzalez</a>
    </th>
    <th>
        <img src="https://avatars.githubusercontent.com/techforchange?s=100" width="100" alt="Arlene Perez" style="text-decoration:none"><br><br>
        <a href="https://github.com/techforchange" style="text-decoration:none">Arlene Perez</a>
    </th>
</table>

Angie and Arlene are LA natives that met while attending Dev Bootcamp in San Francisco.  After bootcamp was over and they were back in LA, they wanted to once again be part of an amazing, welcoming community like DBC was. They found Hoodie through [Rails Girls Summer of Code](https://railsgirlssummerofcode.org/)! This project is extra special for them as it is their first contribution to open source.

### Contributors

Thank you to everyone who has helped with this project.

<table>
  <col width="200">
    <th>
        <img src="https://avatars.githubusercontent.com/michaelmccombie?s=100" width="100" alt="Michael McCombie"><br><br>
        <a href="https://twitter.com/michaelbuilds"  style="text-decoration:none">Michael McCombie</a><br>
        <a href="https://raw.githubusercontent.com/hoodiehq/first-timers-bot/51742c62ae3e4e2be7e58d170a9eab73a3871bf4/assets/avatar.png" style="text-decoration:none">🎨</a>
    </th>
    <th>
        <img src="https://avatars.githubusercontent.com/gr2m?s=100" width="100" alt="Gregor Martynus"  style="text-decoration:none"><br><br>
        <a href="https://github.com/gr2m"  style="text-decoration:none">Gregor Martynus</a><br>
        <a href="https://twitter.com/gr2m"  style="text-decoration:none">👨🏻‍🏫 </a>
    </th>
</table>

This project follows the [all-contributors](https://github.com/kentcdodds/all-contributors) specification.

### License

[Apache 2.0](http://www.apache.org/licenses/LICENSE-2.0)
