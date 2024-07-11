# Rivalz Testnet CLI

This guide provides instructions & commands to download and run the Rivalz client.

## Requirements

```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash
source ~/.bashrc

nvm install 20.0.0
nvm use 20.0.0
```

## Downloads

First, we open the screen on the server where we will install.
```
screen -S rivalz
```

Let's run the command to install CLI
```bash
npm i -g rivalz-node-cli
```
Let's use the command to run Rivalz and enter our EVM address how much cpu and ram we want to use and also enter how much we want to share as storage. Since the maximum shown in storage is the total storage, let's take into account how much free space we have and write it down.

```
rivalz run
```

If the installation was successful, you will see a screen like the one below.

![image](https://github.com/utkubayri/Rivalz/assets/83476028/b69b4c3a-64a8-4e02-bb9e-56a12aa07f76)

CTRL A+D to Close the Screen

**Don't forget to validate the client from Rivalz Dashboard**

Now Let's Get Those Points
