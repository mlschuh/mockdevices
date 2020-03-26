# Usage

## Adjusting

Clone this into your local user directory (`C:\Users\smi\.node-red`). Install the nodered runtime (inside the Installer directory). When it launches, you can ignore the create project and just use the existing one. Any time you deploy, it will update the flow in the `.node-red` folder.

## Packaging

To package into an installer, install innosetup and run the setup build utility with the included `setup_config.iss`. That should spit out an EXE that will put your current project file and all associated requirements into the proper place for nodered to find. The installer does NOT package the nodered-electron installer. 