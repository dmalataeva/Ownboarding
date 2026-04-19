# Ownboarding

Dev setup notes for myself whenever I need to get comfy.

## Dev Dependencies

* [Cursor](https://cursor.com/)
* [Sublime](https://www.sublimetext.com/3)
* [iTerm](https://iterm2.com/downloads.html)
    * Enable dark mode:
        1. Open settings (`Cmd + ,`)
        2. Go to **Profiles** → **Colors** → **Color Presets...**
        3. Select **Dark Background**
        4. Optionally, use this nice theme by adding it to .zshrc: `ZSH_THEME="robbyrussell"`
    * Enable Natural Text Editing:
        1. Open settings (`Cmd + ,`)
        2. **Profiles** → **Keys** → **Key Bindings** → **Key Bindings Presets...**
        3. Select **Natural Text Editing** from list, click **Keep**
* [Zsh](https://ohmyz.sh/)
    * Enable prefix search:
        1. Open `~/.zsh`
        2. Paste:
            ```sh
            # Load prefix search widgets
            autoload -U up-line-or-beginning-search
            autoload -U down-line-or-beginning-search
            zle -N up-line-or-beginning-search
            zle -N down-line-or-beginning-search

            # Bind Arrow Keys
            bindkey "^[[A" up-line-or-beginning-search
            bindkey "^[[B" down-line-or-beginning-search
            bindkey "^[OA" up-line-or-beginning-search
            bindkey "^[OB" down-line-or-beginning-search
            ```
        3. Apply changes

* [Google Chrome](https://www.google.com/chrome/)
    * Also set up [prev/next tab shortcut](#chrome-tab-shortcuts).
* [K8Lens](https://lenshq.io/download/lens-k8s-ide)
* [Docker](https://www.docker.com/get-started/)
* [Postman](https://www.postman.com/downloads/) (Optional)
* [Git](https://git-scm.com/install/mac)
    * Add [SSH key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent).
* Languages, skip whatever not urgent
    * [Rust](https://rust-lang.org/tools/install/) – good to have handy since lots of libs will require it.
    * Go
    * Java
    * Python
    * Node

## CLI

* [Homebrew](https://brew.sh/)
* [vim](https://formulae.brew.sh/formula/vim)
* [Graphite](https://graphite.com/features)
    * Keep [cheatsheet](https://graphite.com/docs/cheatsheet) handy.
* [Cursor/agent](https://cursor.com/cli)
* [Kubectl](https://kubernetes.io/docs/tasks/tools/)
* Docker, docker-compose (included with desktop installation)
    * Keep [cheatsheet](https://docs.docker.com/get-started/docker_cheatsheet.pdf) handy.
* [pyenv](https://formulae.brew.sh/formula/pyenv#default)


## Hotkeys, shortcuts, other sticky things

### Chrome Tab Shortcuts

Use exact Menu Titles:
1. Clear conflicts – move default Back/Forward commands out of the way:
    1. Go to **System Settings** → **Keyboard** → **Keyboard Shortcuts** → **App Shortcuts**.
    2. Click **+**.
    3. Set **Application** to **Google Chrome**.
    4. Set **Menu Title** to `Back`, add random combo (e.g. `Cmd + Option + Shift + B`).
    5. Click **Done**, repeat same for `Forward` (combo suggestion: `Cmd + Option + Shift + F`).
2. Same approach, set `Select Next Tab` to `Cmd + →`.
3. Same approach, set `Select Previous Tab` to `Cmd + ←`.

ℹ️ *If you run into a popup dialogue in Chrome and try to hit either shortcut, the shortcut unsticks and turns back to prev/next page (annoying longstanding bug). Simply restart your browser to get it to stick again.*

### Trackpad

Adjust speed to max.

### Keyboard

Add `Canadian EN` and `Russian - PC` as input sources.

### MacOS Sleep Hot Corner

1. Click the Apple Menu () in the top-left corner and select System Settings (or System Preferences on older macOS versions).
2. In the sidebar, scroll down and click on Desktop & Dock.
3. Scroll all the way to the bottom of the right-hand pane and click the Hot Corners... button.
4. You will see a dialog box with four dropdown menus representing the four corners of your screen.
5. Click the dropdown menu for the Top-Left Corner.
6. Select Put Display to Sleep from the list.

## Productivity

* [Spotify](https://www.spotify.com/de-en/download/other/)
* Remember to log into iCloud to maintain backups and allow devices to sync!