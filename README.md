<div align="center">
  <img align="center" src=".github/images/logo.png" />
  <h1 align="center">Stable Diffusion - Quick Start Guide</h1>
  <p align="center">
    A quick start guide for <a href="https://stability.ai/">Stable Diffusion</a> with the <a href="https://github.com/AUTOMATIC1111/stable-diffusion-webui">AUTOMATIC1111 WebUI</a> for Windows.
  </p>
  <p>
   This is a simple and easy way to get started with Stable Diffusion, a powerful AI tool.
  </p>
</div>

<!---------------------------------------------------------------------------->
<!---------------------------------------------------------------------------->
<!---------------------------------------------------------------------------->

## Index <a name="index"></a>

- [Installation](#installation)
- [Folder Structure](#folder-structure)
- [Running the WebUI](#running)
- [License](#license)
- [Wrapping Up](#wrapping-up)

### Installation <a id="installation"></a>

1. Download and install Python 3.10.x into the `src\py\` folder.

   https://www.python.org/ftp/python/3.10.6/python-3.10.6-amd64.exe

   Choose custom installation, and install to the `src\py\` folder. During installation make sure to uncheck the "Install launcher for all users" option. You can also use newer versions of Python, depending on the project requirements.

2. Download AUTOMATIC1111 WebUI

   https://github.com/AUTOMATIC1111/stable-diffusion-webui/archive/refs/heads/master.zip

   Extract the zip file contents into the `src\ui\` folder.

3. Download and install model(s). A example below:

   - Realistic Vision V5.1 (realistic images, and more)

     https://huggingface.co/SG161222/Realistic_Vision_V5.1_noVAE/tree/main

     Download and move the `Realistic_Vision_V5.1.safetensors` file into:

     `src\ui\models\Stable-diffusion\`

     Note: Only use the .safetensors file, not the .ckpt file. This is a newer, safer format.

That's it! You are now ready to run the WebUI.

<p align="right">[ <a href="#index">Index</a> ]</p>

<!---------------------------------------------------------------------------->
<!---------------------------------------------------------------------------->
<!---------------------------------------------------------------------------->

### Folder Structure (after installation) <a id="folder-structure"></a>

After [installation](#installation), the folder structure should look like this:

```
src\
 ├─ py\                                 # Python 3.10.x
 └─ ui\                                 # AUTOMATIC1111 WebUI
    ├─ models\                          #
    │   └─ Stable-diffusion\            # Your models
    └─ ... (other files and folders)    #
```

<p align="right">[ <a href="#index">Index</a> ]</p>

<!---------------------------------------------------------------------------->
<!---------------------------------------------------------------------------->
<!---------------------------------------------------------------------------->

### Running the WebUI <a id="running"></a>

1. Open `run.bat` at the root of the project, this will launch a command line window and start the server.

2. The browser should open automatically, if not open it manually at:

   http://127.0.0.1:7860/

3. Press `Ctrl + C` to stop the server, within the command line window.

<p align="right">[ <a href="#index">Index</a> ]</p>

<!---------------------------------------------------------------------------->
<!---------------------------------------------------------------------------->
<!---------------------------------------------------------------------------->

## License <a name="license"></a>

This project is licensed under the MIT License. See the [license](/LICENSE.md) file for more
information.

`SPDX-License-Identifiers: MIT`

<p align="right">[ <a href="#index">Index</a> ]</p>

<!---------------------------------------------------------------------------->
<!---------------------------------------------------------------------------->
<!---------------------------------------------------------------------------->

## Wrapping Up <a name="wrapping-up"></a>

Thank you to all that made this project possible!

| Type                                                                      | Info                                                           |
| :------------------------------------------------------------------------ | :------------------------------------------------------------- |
| <img width="48" src=".github/images/ng-icons/email.svg" />                | webmaster@codytolene.com                                       |
| <img width="48" src=".github/images/simple-icons/github.svg" />           | https://github.com/sponsors/CodyTolene                         |
| <img width="48" src=".github/images/simple-icons/buymeacoffee.svg" />     | https://www.buymeacoffee.com/codytolene                        |
| <img width="48" src=".github/images/simple-icons/bitcoin-btc-logo.svg" /> | bc1qfx3lvspkj0q077u3gnrnxqkqwyvcku2nml86wmudy7yf2u8edmqq0a5vnt |

Fin. Happy programming friend!

Cody Tolene
