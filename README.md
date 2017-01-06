![HEKTO](https://cldup.com/RIKwNeeZw4.png)

## Installation
> Hekto is written in node.js and must be installed via npm so you must have [Node.js](http://nodejs.org) installed

```bash
npm install -g hekto
```

## Usage
```bash
cd my-project
hekto serve <path>
```

### Options
| option           | description                                      |
| -----------------| ------------------------------------------------ |
| --version [-v]   | Show the installed version.                      |
| --port \<port>   | The port your static content should be served on |
| --maxage \<maxage>| The maxage for http caching.                     |

### Command
| command| description                |
| -------| ---------------------------|
| serve  | serve the current directory|

## 404 handling
Add a `404.html` file in the top directory.

## Single page applications
Hekto supports single page applications like(react, vue and angular). Simply add a `200.html` file in your projects directory. Hekto will serve your 200.html for all requests. You can still access all the other files.

## Extension less html
Extension less html makes it possible for you to strip `.html` for html files in urls. Eg. `help.html` is served at `/help.html` and at `/help`.

## Contribute
Create a pull request / issue to tell us about your awesome ideas, you want us to add or fork the repo and send us a link to your version.

## License
MIT
