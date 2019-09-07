<p align="center">
  <img src="juno_app_icon_logo.png" width="300"/>
</p>

This is an **issue tracker** for Juno, an app running Jupyter locally on your iOS device (currently only distributed via TestFlight).

<p align="center"><a href="https://testflight.apple.com/join/XRjYzgMU"><b>🚀 Install via TestFlight</b></a></p>

Please, report any requests or defects you encounter with Juno by [opening an issue](https://github.com/navoshta/Juno-Issue-Tracker/issues/new/choose) in this repo. Also, please report any modules or packages that you would like to be pre-installed. Don't forget to [search for existing issues](https://github.com/rationalmatter/Juno-Issue-Tracker/issues) first, in case someone else has reported your thing already — and if someone has, rather comment on existing issue. Please, _do not_ report issues with the [Juno client](https://juno.sh) here (i.e. the one available on the AppStore, the Jupyter client app).

### Reporting issues
Juno is currently in active development, so I expect quite a few things not to work — please, report anything you notice that doesn't feel right.

### Pre-installed packages
Juno currently ships with **Python 3.6.6** kernel and following packages pre-installed:
* NumPy 1.16.4
* Matplotlib 3.1.1
* Pandas 0.25.0

### Installing pure Python modules
In order to install other pure Python modules, you can use PyPI installer in Juno (top bar, icon with an arrow). Simply provide package name (the one you would use with `pip` command), and it will let you select package version and install into your `/site-packages` directory. It will only manage to successfully install pure Python packages due to OS restrictions, therefore currently only source and purelib wheel distributions are supported. Mind that dependencies are **NOT** installed automatically, you need to install each manually.

Installer is "stateless", which means it doesn't keep track of what has been installed previously, and simply overwrites whatever is currently installed. If you would like to remove a package, simply delete its folder in `/site-packages` directory.

Alternatively, you can copy pure Python packages directly into `/site-packages` folder in Juno documents via iOS's Files app, and you should then be able to import them in your notebooks.

<br>
<p align="center"><a href="https://github.com/navoshta/Juno-Issue-Tracker/issues/new/choose"><b>⚠️ Open a new issue</b></a></p>
