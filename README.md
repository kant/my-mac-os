# my-mac-os

List of hardware, applications, and tools that make my macOS experience amazing, inspired by https://github.com/nikitavoloboev/my-mac-os (with shameless copy pasting (I hope that's ok 🙏🏼) where I couldn't find better wording).

![](https://imgur.com/K5uLtya.png)

##### Contents

- [Hardware](#hardware)
- [Applications](#applications)
  - [Productivity](#productivity)
  - [Code](#code)
  - [Social](#social)
  - [Writing](#writing)
  - [Music](#music)
  - [Images](#images)
  - [Utilities](#utilities)
  - [Browsers](#browsers)
- [Command Line Apps](#command-line-apps)
- [Preference Panes](#preference-panes)
- [Similar Setups](#similar-setups)
- [Related](#related)
- [Contributing](#contributing)

## Hardware

Computer: 15" Late 2016 Macbook Pro with Touch bar.

Trackpad: [Apple Magic Trackpad 2](https://www.amazon.com/Apple-Magic-Trackpad-2-MJ2R2LL/dp/B016QO5YWC/ref=sr_1_3?ie=UTF8&qid=1538413611&sr=8-3&keywords=apple+magic+trackpad).

Monitor(s): [2x Dell U2417H](https://www.amazon.com/Dell-U2417H-UltraSharp-LED-Backlit-Monitor/dp/B01D11JUAU).

Keyboards:
- [Matias Ergo Pro](https://matias.ca/ergopro/pc/) for work and programming.
- [Microsoft Universal Foldable Keyboard](https://www.amazon.com/Microsoft-Universal-Foldable-Keyboard-Android/dp/B00UBGU4PY) for typing on the go.
- [Filco Majestouch Ninja 2](https://www.amazon.com/Filco-Majestouch-2-Keyboard-FKBN104M-EFB2/dp/B004Z0XR2O/ref=sr_1_1?s=electronics&ie=UTF8&qid=1538413535&sr=1-1&keywords=filco+majestouch+ninja+2) for gaming.

## Applications

I'm slowly transitioning to cross-platform software because I want to be able to use the majority of my apps on any OS.

### Productivity

#### [Alfred](https://www.alfredapp.com) - Launcher

- Alfred is both my launcher, clipboard history manager, and entry point to lots of [awesome workflows](https://wiki.omar.engineer/alfred/workflows).

  <img src="https://i.imgur.com/zzF5Bkk.png" width="700" alt="img">

- It has a great [community](http://www.alfredforum.com/) and [amazing workflows](https://github.com/learn-anything/alfred-workflows#readme) that you can use.

Here's a small example of me using it to quickly run/evaluate Ruby code:

![](https://imgur.com/eCdrvs2.png)


#### [Todoist](https://todoist.com/) - Simple and quick task manager

- Todoist helps me plan out everything I want to do either for the short term or long term (I'm not sure if I follow GTD).
- It also has global quick add with a hotkey. Together with lists, priorities, powerful search and a lot more.

  <img src="https://i.imgur.com/QicIQmD.png" width="400" alt="img">


#### [Trello](https://trello.com) - Project management tool

- Simple project management tool with tons of great integrations.

#### [Pipefy](https://pipefy.com) - Automation on boards and forms

- When I need something like Trello but with a lot more automation/power (e.g. having a public form, sending emails when things move to a certain column, triggering other actions, etc.)

#### [1Password](https://1password.com) - Password manager

- Generate all of my passwords with it and keep everything in a secured and encrypted vault kept secure by a master password and two factor authentication.
- No longer need to remember passwords and I now have a unique password for every website that I am signed up on whilst [activating two factor authentication](https://support.1password.com/one-time-passwords/) wherever possible.

#### [MindNode](https://mindnode.com) - Interactive Mind Mapping

- I write A LOT, too much actually, MindNode helps me write short summaries of my thoughts that I "connect the dots" (or lines) between.

#### [PDF Expert](https://pdfexpert.com/) - PDF reader/editor

- Super fast PDF viewer.
- Best experience for editing PDFs or filling PDF forms.


#### [Contexts](https://contexts.co) - Window switcher

- Allows me to fuzzy search through all the currently active windows that I have.

![](https://i.imgur.com/vO9sDbN.png)

- Makes jumping to the right window I need effortless. I often may have many VS Code instances with different projects running and this lets me switch to the project I need in seconds.

#### [Bartender](https://www.macbartender.com/) - Menu bar organizer

- Allows you to customize and hide the contents of your menu bar and improve the aesthetics of your OS. Here is how mine looks:
  <img src="https://i.imgur.com/GKjbmZJ.png" width="500" alt="img">

#### [Magnet](http://magnet.crowdcafe.com/) - Organize your workspace

- Lets me use keyboard shortcuts (or more rarely, drag-drop to edges) to tile windows on my screen.
- Keyboard shortcuts to move windows across monitors.

#### [Yoink](https://eternalstorms.at/yoink/mac/) - Simplify and Improve Drag and Drop on your Mac

- A small/quick utility I use to drop files from multiple locations/apps into to take an action on them later.

#### [Little Snitch](https://www.obdev.at/products/littlesnitch/index.html) - Control incoming/outgoing network traffic

- Amazing networking tool that gives you a clear picture of what connections are incoming to your computer and what are outgoing.
- Takes a bit of time to set it up correctly and is quite an insightful experience first turning it on and having it notify every couple of seconds that some app is trying to send data to some server and whether you want to allow that.
- This is essential if you want to take control of what information gets sent out from your computer and what connections have right to connect to your data.

### Code

#### [Visual Studio Code](https://github.com/Microsoft/vscode) - Code editor

- My favorite editor that I use to write code in. I use [many extensions](https://wiki.omar.engineer/vscode/extensions) for it.
- I use the [Nord](https://marketplace.visualstudio.com/items?itemName=arcticicestudio.nord-visual-studio-code) theme, [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme) and the [Pragmata Pro](https://www.fsd.it/shop/fonts/pragmatapro/) font.

Here is how it looks:

![](https://imgur.com/4NQb6wu.png)

#### [Neovim](https://neovim.io/) - Powerful text editor

- Opening, editing, modifying, and searching through huge files.
- Go-to commandline text editor.
- I use [vim-plug](https://github.com/junegunn/vim-plug) to manage plugins.

#### [Hyper](https://hyper.is/) - Terminal Emulator

- I use Fish as my shell together with [Fisher](https://github.com/jorgebucaran/fisher) to install [Fish plugins I use](https://wiki.omar.engineer/fish/plugins).
- You can find my dotfiles [here](https://github.com/obahareth/dotfiles).
- I use the [Pure prompt](https://github.com/rafaelrinaldi/pure) and the [Nord theme](https://github.com/arcticicestudio/nord-hyper).

![](https://imgur.com/AbjcLCd.png)

#### [Dash](https://kapeli.com/dash) - API Documentation Browser

- Allows you to download any docset that you might want to use, search for any method, class or anything that you need very quickly, comes with the amazing [Alfred workflow](https://www.alfredapp.com/blog/productivity/dash-quicker-api-documentation-search/) to simplify the process of searching for the right things.


#### [GitKraken](https://www.git-tower.com) - Git client

- Great cross-platform Git client that integrates well with GitHub, BitBucket, GitLab, and supports GitFlow.

#### [Kaleidoscope](https://www.kaleidoscopeapp.com/) - Powerful diff tool

- Really great, precise, and beautiful diffing.
- Great at viewing/merging conflicts.
- Can do directory and image diffs as well.

#### [Gitify](https://github.com/manosim/gitify) - GitHub issue & pull request notifiations

- Neat little app that sits in the menu bar and lights up when I have GitHub notifications.
- Can view all notifications and mark them as read.

### Social

#### [Textual](https://www.codeux.com/textual/) - IRC Client

- The best macOS IRC client I've found.


#### [Rambox](https://github.com/ramboxapp/community-edition) - Open Source Multi-messaging App

- A single app I use for chatting with people on:
  - Telegram.
  - WhatsApp.
  - Messenger.
  - Discord.

#### [Slack](https://slack.com) - Work chat

- Chatting for work.
- Collaborating with people on some open source projects and great communities.
- I use the [Nord theme for the sidebar](https://github.com/arcticicestudio/nord-slack) and also apply a [Nord stylesheet](https://github.com/tborychowski/slack-nord-theme) so everything looks Nord-ish.

It looks a bit like this (the screenshot is from the slack-nord-theme repo):

![](https://github.com/tborychowski/slack-nord-theme/raw/master/screen.png)


#### [Mailspring](https://getmailspring.com) - Email client

- Open source.
- Great dark theme.
- I approach all of my email tasks in GTD style. Keeping my email Inbox close to 0 at all times.

### Writing

#### [Day One](http://dayoneapp.com/) - Digital journal

- Day One is my digital life journal.
- If you don't journal, I suggest you to start, it is a very powerful mind cleanser and acts as a wonderful history record of your life.

#### [Byword](https://bywordapp.com/) - Distraction-free Markdown Editor

- A great minimal distraction-free markdown editor, I use it when I want absolute focus.

#### [Quiver](http://happenapps.com/) - The Programmer's Notebook

- Powerful cell-based editor that operates based on "cells" (e.g. markdown cell, code cell, LaTeX cell, etc.) for mixing and matching different kinds of formats.
- Plain JSON data format.
- Cloud syncing.
- Charts.

#### [Notion](https://notion.so) - Large writing, scans, web clips, and annotations

- I do my huge writing here.
- If I want to access a document from anywhere, I usually store it here.

### Music

#### [Google Play Music](https://play.google.com/music) - Music Streaming

- My goto music streaming solution.
- Easiest for me to setup from where I live (Saudi Arabia).

#### [YouTube Music](https://music.youtube.com/) - Music Streaming 2nd solution

- Google Play Music will most likely be merged with this, so it might be best to get used to it.
- I use it on the rare occasion that I don't find something on Google Play Music.

### Images

#### [Google Photos](https://photos.google.com/) - Cloud storage for photos

- Easiest way to backup my photos and access them from multiple places.
- Machine learning, auto detects images.
- 😖 Kind of scary.

### Utilities

#### [xScope](https://xscopeapp.com/) - Measure. Inspect. Test.

- A powerful set of tools for Mac OS X that are ideal for measuring, aligning and inspecting on-screen graphics and layouts.

#### [iStat Menus](https://bjango.com/mac/istatmenus/) - Mac system monitoring from menu bar

- Great system monitoring tools which I use to quickly see my CPU/network/memory usage.
- Has a great calendar popup that shows when you click date/time in the menubar. This is something I was really used to from Windows/Linux that I'm glad to have back again.

#### [HyperDock](https://bahoom.com/hyperdock) - Window Previews for Dock

- Window previews (thumbnails) when hovering over applications on the dock.
- Calendar previews when hovering over the Calendar.

#### [Insomnia](https://insomnia.rest/) - Great API tool

- Full-featured HTTP client that lets you test and describe the APIs you build or consume.
- Open source.
- Cross-platform.

### Browsers

#### [Google Chrome](https://www.google.com/chrome/)

- My main web browser because it easily syncs my extensions across machines.
- I use [these extensions](https://wiki.omar.engineer/google-chrome/extensions) and [this theme](https://wiki.omar.engineer/google-chrome/theme).

#### [Safari](https://www.apple.com/lae/safari/)

- Incredibly fast/lightweight web browser.
- Since I don't have extensions on it, I use it for when my Chrome extensions break sites.


## Command Line Apps

- [autojump](https://github.com/wting/autojump) - A cd command that learns, easily navigate directories from the command line.
- [asdf](https://github.com/asdf-vm/asdf) - One version manager for all my programming languages.
  - [elixir](https://github.com/asdf-vm/asdf-elixir)
  - [golang](https://github.com/kennyp/asdf-golang)
  - [java](https://github.com/skotchpine/asdf-java)
  - [nodejs](https://github.com/asdf-vm/asdf-nodejs)
  - [redis](https://github.com/smashedtoatoms/asdf-redis)
  - [ruby](https://github.com/asdf-vm/asdf-ruby)
  - [rust](https://github.com/code-lever/asdf-rust)
- [fzf](https://github.com/junegunn/fzf) - Command-line fuzzy finder.
- [colorls](https://github.com/athityakumar/colorls) - Beautify `ls` command with color and font-awesome icons.
- [bat](https://github.com/sharkdp/bat) - Cat clone with wings.
- [git](https://github.com/git/git) - Version control.
- [curl](https://curl.haxx.se/docs/manpage.html) - Transfer data from or to a server.
- [htop](https://github.com/hishamhm/htop) - Interactive text-mode process viewer for Unix systems.
- [httpie](https://github.com/jakubroztocil/httpie) - HTTP client.
- [curl](https://github.com/curl/curl) - Transfer data, supports various protocols.
- [howdoi](https://github.com/gleitz/howdoi) - Instant coding answers.
- [asciinema](https://github.com/asciinema/asciinema) - Terminal session recorder.
- [tldr](https://github.com/tldr-pages/tldr) - Simplified and community-driven man pages.
- [now](https://github.com/zeit/now-cli) - Real time global deployments served over HTTP/2.
- [yarn](https://github.com/yarnpkg/yarn) - Fast, reliable, and secure dependency management.
- [hub](https://github.com/github/hub) - GitHub wrapper.
- [xsv](https://github.com/BurntSushi/xsv) - Fast CSV command line toolkit written in Rust.

## Preference Panes

- [GPG Suite](https://gpgtools.org/) - Encrypt, decrypt, sign and verify files or messages.
  - I use this also for signing my commits.

## Desktop Screenshot

![](https://imgur.com/K5uLtya.png)

> Using [screenfetch](https://github.com/KittyKatt/screenFetch)

## Similar Setups

Here you can find more setups by other people that you can take ideas and inspiration from.

- [The original `my-mac-os`](https://github.com/nikitavoloboev/my-mac-os) - The original repo that acted as inspiration for me to build this one.
- [Works for me](https://works-for-me.github.io/) - Collection of developer toolkits.
- [Use This Interviews](https://usesthis.com) - What do people use to get stuff done?

## Related

- [Awesome mac](https://github.com/jaywcjlove/awesome-mac#readme)
- [Interesting macOS apps](https://github.com/learn-anything/macos-apps#readme)
- [Open Source macOS apps](https://github.com/serhii-londar/open-source-mac-os-apps#readme)

## Contributing

If you shared a similar personal setup to this, be it for Windows, Linux or anything else, you can add it in [Similar Setups](#similar-setups) section.

I love finding new awesome tools and apps. If you have a favorite tool or app that you think I missed, please [say it](../../issues/new).
