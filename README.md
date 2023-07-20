## Automatic installation

### New install:

1. If Homebrew is not installed, follow the instructions at https://brew.sh to install it. Keep the terminal window open and follow the instructions under "Next steps" to add Homebrew to your PATH.
1. Open a new terminal window and run `brew install cmake protobuf rust python@3.10 git wget`
1. Clone the web UI repository by running `git clone https://github.com/AUTOMATIC1111/stable-diffusion-webui`
1. Place Stable Diffusion models/checkpoints you want to use into `stable-diffusion-webui/models/Stable-diffusion`.
1. `cd stable-diffusion-webui` and then `./webui.sh` to run the web UI. A Python virtual environment will be created and activated using venv and any remaining missing dependencies will be automatically downloaded and installed.
1. To relaunch the web UI process later, run `./webui.sh` again. Note that it doesn't auto update the web UI; to update, run git pull before running `./webui.sh`.

### Existing Install:

If you have an existing install of web UI that was created with `setup_mac.sh`, delete the run_webui_mac.sh file and repositories folder from your stable-diffusion-webui folder. Then run git pull to update web UI and then ./webui.sh to run it.
