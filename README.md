# createquick
A simple shell script that manages project/document templates
## Installation
Clone the git repo and cd into the folder: `$ git clone https://github.com/xypwn/createquick.git && cd createquick`
Run the install script: `$ sh install-sh`
(Optional) Delete the git repo: `$ cd ..; rm -rf createquick`
## Usage
For the help page, enter `$ cq -h`
- You can list out all available templates with `$ cq -L`
### Creating templates
- Create a folder and put your template files in it
- In the folder, run: `$ cq -c <template name>`
### Loading templates
- Simplest: `$ cq <folder name>` will put you into a TUI where you can select a template, the contents of which will then be put into a folder with the specified name in you current directory
- See the help page for further options
