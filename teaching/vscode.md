# Installation

The latest version can be downloaded from [official website](https://code.visualstudio.com), and it is pretty straight forward. After installation, you can follow the [videos](https://code.visualstudio.com/docs/getstarted/introvideos) to start your journey!

# Extension

One of the best things I love about VScode is that it provides millions of extensions to customize it in your own way. It is similar to the Chrome browser extensions, and you can find it on the toolbar on the left after you open VScode. Here is a list of extensions that I find very useful:
- Jupyter
- Markdown All in One
- Prettier - Code formatter
- Python
- R
- Remote - SSH (which we will use to connect to remote server)
- Rainbow CSV

Please note that if you install too many extensions, VScode will take a longer time on initial startup. Under the `LOCAL-INSTALLED` in the extensions, you can actually see how much time each extension requires (generally several ms). I suggest to check this from time to time, and remove those extensions that you haven't used for a long time and take a long time loading. You can also read [this](https://www.roboleary.net/2021/08/10/vscode-how-many-extensions-should-i-use.html) for more information.

# Connect to remote server

Generally when you open your VScode, it is in the local environment. However, in practice, almost everything is on our cluster. Luckily, VScode provides a way to connect to the remote server. Before you start to connect, make sure that you know how to connect to the cluster in command line (using `ssh`) and all necessary passwords. An extension, [Remote-SSH](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-ssh) is also required.

Details of setup can be found [here](https://code.visualstudio.com/docs/remote/ssh).

After the setup, you can check which host you are connected to in the Status Bar (at the bottom, if not seen, go to `View -> Appearance -> Status Bar`).

The next time you want to connect to the cluster, just go to `View -> Command Palette` (on Mac, you can use `cmd+Shift+p`), then type `Remote-SSH: Connect to Host` after `>`. And you are good to go!

#



