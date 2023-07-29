# Aptos Cheatsheet
#
# Aptos official installation guide:
#  https://aptos.dev/tools/aptos-cli/install-cli/automated-install
#
# As of writing this cheatsheet (July 2023), a prerequisites for the machine:
##  1. Have python 3.6+ installed on the machine you are working on
#
# For Windows user, after checking the correct version of python is install, open WSL (Windows Subsystem for Linux), then use one of the following command to install Aptos CLI:
##  curl -fsSL "https://aptos.dev/scripts/install_cli.py" | python3
##  wget -qO- "https://aptos.dev/scripts/install_cli.py" | python3
#
# After installing follow the suggestion to add Aptos CLI to the PATH environment variable, which should be something similar to:
## export PATH="/home/WSLName/.local/bin:$PATH"
#
# After inserting the PATH, restart WSL before continuing.
#
# To make sure we are using the latest Aptos CLI, trigger an update by using one of the following:
##  aptos update
##  python3 install_cli.py
#
# At this point, if no there is no error message pops up, Aptos CLI should be successfully installed.  But to ensure this is the case, we can verified the installing using the following command (if successful, should return a verification code):
##  aptos account list --account 0x7569642d636c6b616d33306e38303030386c38303830697630756f3137 --url https://www.overmind.xyz/api/fullnode
#
