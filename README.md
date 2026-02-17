<div align="center">
<img src= "https://raw.githubusercontent.com/Janglee123/eplee/master/build/icons/256x256.png" width="200px" height="200px">
<p></p>
<h2>Eplee</h2>
Sweet, Simple and Beautiful ePub reader<br>

<a href="https://dev.azure.com/merupatel123/test2/_build/latest?definitionId=2&amp;branchName=master">
  <img src="https://dev.azure.com/merupatel123/test2/_apis/build/status/test2-CI?branchName=master" alt="Build Status">
</a>

<a href="https://www.codacy.com/app/Janglee123/eplee?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=Janglee123/eplee&amp;utm_campaign=Badge_Grade">
  <img alt="Codacy grade" src="https://img.shields.io/codacy/grade/425ba0a050424bb08aeb15f9b7bcd263.svg?logo=Codacy">
</a>

<a>
<img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs welcome!" />
</a>

<a href="https://github.com/Janglee123/eplee/releases">
<img alt="GitHub All Releases" src="https://img.shields.io/github/downloads/janglee123/eplee/total.svg?label=Downloads&logo=GitHub">
</a>
</div>

"Eplee is an ePub reader focused on clean distraction-free reading experience with simple and beautiful UI."

## NOTE:

** This fork is under active development.  I do not suggest using anything here until this note is removed and the version number being changed to 0.5.0 as I suspect this may become an entirely different github project. **

## Screenshots

![](https://raw.githubusercontent.com/Janglee123/eplee/master/screenshots/screenshot_2.png) ![](https://raw.githubusercontent.com/Janglee123/eplee/master/screenshots/screenshot_1.png)

## Features

- Clean UI 
- Easy Navigation
  - Table of content
  - Slider
  - Use swipe, wheel, arrow key or mouse to flip page  
- Bookmark
- Highlights
- In Book search
- Themes (Light, Tan, Dark)
- Custom style support
- Language translation
- Continue reading where you left

## Why this fok? (2026)

First, the legacy: Janglee wrote:
> There are lots of open source epub reader available right now. So, the question "Why there is a need for another epub reader?" is meaningful.
> The answer is the reading experience. Eplee focused on clean UI that let you read a book without annoying GUI.

I like many things about this code-base, however the original was archived in December, 2022.  That means we've had three years of awesome VueJS and other improvables. It is almost easier to reconfigure the application as a PWA first, then add Electron later.

## Development

I have three use cases which I plan to complete with this fork:

* The ability to "SQL query" certain kinds of ebooks to pull out content, and let the user make their own smaller versions such that they can make smaller custom ebooks, such as collected short stories, sheet music, etc.
* The ability to use certain kinds of translator tech to allow a user to:
** read, 
** suggest, 
** possibly edit, 
** approve edits and translations
* iterate.
* Finally... I am hoping to develop a multi-functional CSS pattern which will allow users to print out books including printer-type specific options.

## Github Related:

Clone this repository

```bash
git clone https://github.com/PaulCEllsworth/eplee
```

change directory to the cloned path

```bash
cd eplee
```

Install dependencies

```bash
yarn
```

Start app

```bash
yarn run dev
```

## Built With

- [vuejs](https://vuejs.org/)
- [element ui](https://element.eleme.io/#/en-US)
- [vue-electron-template](https://github.com/mubaidr/vue-electron-template)
- [epubjs](https://github.com/futurepress/epub.js/)

## Contributing

PRs are welcome. Feel free to contribute. 

# License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/Janglee123/eplee/blob/master/LICENSE) file for details.
