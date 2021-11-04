# Why Vue Is Awesome - The Prep

So you want to learn why Vue is awesome, thats awesome which makes you awesome.

Part of the training you will be writing some code (exciting I know) so you will need to make sure your laptop is setup so you can follow along. Dont worry if you dont want to follow along thats cool too and you can skip this and just show up on the day :D

To follow along you will need the following, and i imagine you will have most of them already.

* A mac (sorry windows peeps)

* Brew (and an actual Brew :coffee:)

* VSCode with the following plugins
  * Vetur

* Node LTS

---

## Install Brew

Im not going to walk you through this because the people that write brew will be a lot better at that, you can find pretty much everything you ever need to know about brew [here](https://brew.sh/ )

## Installing Node

When writing code with Node you will normaly end up using different versions depending on the project, so to allow you to switch between Node version easily and keep all the modules you install seperate we will be using a tool called [NVM](https://github.com/nvm-sh/nvm) (Node Version Manager).

Installing NVM is easy with Brew (you will need admin rights, use the selfservie tool before install)

``brew install nvm``

Once that commadn completes you will be asked to carry out a couple of other task to finsih the install and to begin using NVM, it should look somthing like this but please check your own output

```bash
You should create NVM's working directory if it doesn't exist:

  mkdir ~/.nvm

Add the following to ~/.zshrc or your desired shell
configuration file:

  export NVM_DIR="$HOME/.nvm"
  [ -s "/usr/local/opt/nvm/nvm.sh" ] && . "/usr/local/opt/nvm/nvm.sh"  # This loads nvm
  [ -s "/usr/local/opt/nvm/etc/bash_completion.d/nvm" ] && . "/usr/local/opt/nvm/etc/bash_completion.d/nvm"  # This loads nvm bash_completion
```

You then need to reload your terminal either by closing and re-opening the window or by re-sourcing your config file, if you are using zsh (which I highly recomend) run the following.

``source ~/.zshrc``

You should now be able to confirm that NVM was install correctly by running

``nvm --version``

You should get somthing back like

``0.39.0``

Your now good to install node, for this training/project we will be using the latest LTS (Long-Term Support), to install that you will need to run 

``nvm install --lts``

at the time of writing this the current LTS version is v16.13.0, you can check whcih version of node is install two ways

``nvm current``
or
``node --version``

Both commands should return the same version number.

If it does AWESOME, if not give me a message on teams

You should now be ready for the training/course, if you have any issues at any point let me know and i will try to help you out.
