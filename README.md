# MyBinder.org Class Template

This project intends to provide a class template. The template has a Dokcerfile that installs Yandex.Disk agent.

With this agent, the users of this template will have a way to persist the outcomes of what they are doing in MyBinder.org.

PS.: MyBinder.org doesn't encourage anyone to store passwords in their running instances. Use your Yandex.Disk credentials in ?Mybinder.org at your own risk.

## Usage

pS.: You will need a Yandex.Disk account. Go to disk.yandex.com and create one.

1. Go to https://mybinder.org/v2/gh/rafael-ladislau/mybinder-class/master?urlpath=%2Flab and open a terminal.
2. Execute the command `yandex-disk setup`
3. Select 'n' in "Would you like to use a proxy server? [y/N]:"
4. Type your credentials
5. Hit 'Enter' in "Enter path to Yandex.Disk folder (Leave empty to use default folder '/home/jovyan/Yandex.Disk'):"
6. Finally, Hit 'Enter' in "Would you like Yandex.Disk to launch on startup? [Y/n]:"

A folder called "Yandex.Disk" will show up in the left menu (File Explorer), and everything you save there will be persisted at Yandex.Disk.
