# Interfaces
Interfaces for EQEmu  
(Not compatible with P99)

## Usage
### Quickest/Easiest
- Download ZIP of the repository 
- Copy the directories to `<install_directory>/EverQuest/uifiles/`
- Start the game and load the UI with `/loadskin <skin_name>`
### Recommended
- Clone the repository `git clone https://github.com/titanium-forever/Interfaces [optional_directory_name]`  
- Symlink from EQ UI directory to the desired skin:  
  - Linux: `ln -s <clone_directory>/<skin> <install_directory>/EverQuest/uifiles/<skin_name>`  
  - Windows: `mklink <install_directory>\EverQuest\uifiles\<skin_name> <clone_directory>\<skin>`  