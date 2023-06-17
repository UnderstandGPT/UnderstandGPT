---
sidebar_position: 3
---

# Deploying an Ooba Instance

There are two primary methods of standing up an Oobabooga interface

### Direct via Python

Most LLMs and applications built around them are Python based. As such, setting up Python directly can be a direct path to running LLMs or interfaces.

It is recommended to use **Python 3.10+** as many interfaces and modules are built around features available from this version onwards. 

To setup Python on your system:

##### Windows

Install Python 3.10+ from [Python.org](https://www.python.org/downloads/)

##### Linux

Check if Python is pre-installed with your OS:
```
python3 --version
```

If Python 3.10+ is not available, follow this [guide](https://docs.python-guide.org/starting/install3/linux/) to install it.

##### MacOS

Install Python 3 with Brew:
```
brew install python
```

If you do not have `brew` installed, please follow the Install process [here](https://brew.sh/).

### In a Container w/ Docker

One disadvantage of a direct Python deployment is the inability to quickly replicate that environment. Say you want to share your setup with others or if an error occurs.

Docker can allow you to easily replicate, share or even redeploy your interface or application. 

##### Docker for Windows

[Install Docker Desktop for Windows](https://docs.docker.com/desktop/install/windows-install/)

##### Docker for Linux

Utilize the Docker provided [convenience script](https://docs.docker.com/engine/install/ubuntu/#install-using-the-convenience-script)

##### Docker for MacOS

[Install Docker Desktop for MacOS](https://docs.docker.com/desktop/install/mac-install/)

### Proceeding with Setup

Now that you have Python and/or Docker installed, you can continue on to deploying Oobabooga text-generation-ui.

- [Python setup instructions](https://github.com/oobabooga/text-generation-webui#installation)
- [Easy setup with Docker](https://github.com/Atinoda/text-generation-webui-docker)