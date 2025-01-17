# Vivaldi (Browser)
Download [Scoop](https://github.com/BosEriko/scoop) as your package manager then install [Vivaldi](https://scoop.sh/#/apps?q=vivaldi).

## Install Vivaldi
```sh
scoop bucket add extras
scoop install extras/vivaldi
```

## Sync your settings
Go to the folder where you want to put your Vivaldi files and run the following script.
```sh
curl -fsSL https://raw.githubusercontent.com/BosEriko/vivaldi/HEAD/install.sh | sh
```

## Update your settings
Follow this [instruction](instruction.md) to update your settings. Then update your [hotkeys](hotkeys.md).

## Developer Tools of Vivaldi UI
To open the Developer Tools of the UI you can do:
- Open Vivaldi and navigate to `vivaldi://inspect/#apps/`
- Click “inspect” beneath the second line (Vivaldi window.html)