# About QBJS

QBJS is an implementation of the Basic programming language for the web, with multimedia support and easy sharing of programs. It aims to be compatible with QB64, which in turn implements the same dialect as the classic QBasic.

The project is in active development as of 30 March 2022. It can be tried online on itch.io; documentation and releases are hosted on GitHub.

Support for browser APIs is built-in as of version 0.3.0-beta; a game engine is included separately.

# About the vscode template

## Setup:
1. Clone this repo
2. Open vscode
3. Install the recommended extensions
4. Restart vscode (if applicable)
5. Open `index.bas` and start coding
6. Press `F5` to build and preview

> NOTE: index.html, index.bas, and index.js are all just placeholder names, and
> you could use other names. If you do, make sure that if you modify index.html
> to another name, the liveServer web preview won't find it by default, so you
> will need to open the html file, and click the preview icon.
>
> `index.js` is linked via `<script>` tag in the `index.html` and so if you do
> rename that file, you will need to modify `index.html` as well.


### If you don't have qb2js for your platform...
1. Clone the qbjs repo
2. Compile tools/qb2js.bas
3. Copy the qb2js binary into root of project
4. Modify tasks.json to use qb2js platform command

> In the future I will include separate tasks depending on the OS.