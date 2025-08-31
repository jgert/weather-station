

## Install fonts
Take a look into [Fonts](resources/fonts/README.md)

## Autogenerate font headers

```bash
cd ./tools/cli
# Optionally, create local venv
python3 -m venv .venv
# Optionally, activate local venv
source .venc/bin/activate
# Install required python dependencies
pip3 install -r requirements.txt
# execute tool
./main.py --help
# or execute as everything is set to run for this repo
./main.py config.json
```
