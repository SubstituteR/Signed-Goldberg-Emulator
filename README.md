# Signed-Goldberg-Emulator
Some third party tools may show nag-screens if Goldberg Emulator is used to run the game in offline mode / without Steam.
One method of detection is checking if the Digital Signature is valid for the steam_api files.
This repo contains self-signed steam_api files and includes the required .cer file.

~~On 21.18.2020 the pfx file used to sign these will be added to this repo. This self-signed cert expires 20.18.2020.~~
The expired pfx file has been uploaded. The pfx password is "password"

The steam_api files are timestamped, so this short expirey is not an issue (for using), and was chosen explicitly for security purposes.


# Using
Run "Install Cert.bat" and click "yes"

# Removing
Run "Remove Cert.bat" and click "yes"
