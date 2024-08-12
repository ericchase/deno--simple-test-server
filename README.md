Basic web server for test environment using Bun (https://bun.sh/)

### Features

- Auto-increment when preferred **port** is in use
- File serving from **public** directory
  - URL path normalization
- Bun provides **MIME** types in responses by default

### Examples Pages

- Basic html page that loads a stylesheet and script.
  - /example-site/index.html
- Basic html page that loads a stylesheet and script as module.
  - /example-site-modules/index.html
- Mock page for handling **CORS** Preflight checks (the HTTP OPTIONS Request)
  - /example-database-access.html

### Installing Bun

- Install the latest version of Bun from their website:
  - [https://bun.sh/](https://bun.sh/)

### Running the Server

- Windows

  - Run `server.bat` or `server.ps1`\*
  - \*running powershell scripts directly requires [security bypass](https://learn.microsoft.com/en-us/powershell/module/microsoft.powershell.core/about/about_run_with_powershell?view=powershell-7.4)

- Linux
  - Run `bun server.ts`
