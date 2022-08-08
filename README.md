# dotify

dotify is an application that lets you generate dotfile repository and update it. It's based on the [dotman](https://github.com/Bhupesh-V/dotman) application created by Bhupesh Varshney (credits to him). It's a reboot to that application, which got abandoned in 2020.

## How to install

It can be installed either locally on your home directory or system-wide.

### cURL

* Local install

```shell
curl -fsSL https://raw.githubusercontent.com/Aptivi/dotify/main/dotify > $HOME/dotify
chmod +x $HOME/dotify
```

* System-wide install

```shell
curl -fsSL https://raw.githubusercontent.com/Aptivi/dotify/main/dotify | sudo tee /usr/local/bin/dotify
sudo chmod +x /usr/local/bin/dotify
```

### WGet

* Local install

```shell
wget -O$HOME/dotify https://raw.githubusercontent.com/Aptivi/dotify/main/dotify
chmod +x $HOME/dotify
```

* System install

```shell
sudo wget -O/usr/local/bin/dotify https://raw.githubusercontent.com/Aptivi/dotify/main/dotify
sudo chmod +x /usr/local/bin/dotify
```

## Features

* Update remote dotfile repository
* Push changes to remote
* Copy dotfiles from local to remote
* Sync dotfiles to local
* An option to copy dotfolders with the files

## License

```
MIT License

Copyright (c) 2022 Aptivi

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

