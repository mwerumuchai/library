# Console Application
#### Created by [Esther Muchai](https://github.com/mwerumuchai) 

## Setup/Installation Requirements

### Prerequisites
* .NET CORE
* .Net Command Line Interface (cli) Tools
* Visual Studio Code

### Installation Process
1. Copy/Download repository link
2. Run `git clone https://github.com/mwerumuchai/library.git` in your terminal
3. Write `cd library`
4. Run `dotnet add package Newtonsoft.Json`
5. Run `dotnet run`

### New installation
* sudo apt-get install apt-transport-https
* sudo wget -q https://dl-ssl.google.com/linux/linux_signing_key.pub -O- | sudo apt-key add -
* sudo sh -c 'echo "deb [arch=amd64] https://packages.microsoft.com/repos/microsoft-ubuntu-xenial-prod xenial main" > /etc/apt/sources.list.d/dotnetdev.list'
* sudo apt-get update
* sudo apt-get install dotnet-sdk-2.1.4
* dotnet --version

1. Run `dotnet new console -o <app-name>`
2. Navigate to folder : cd <app-name>
3. Run `dotent run`

MIT (c) 2018 [Esther Muchai](https://github.com/mwerumuchai)
