<p align="center">
  <img src="juno_app_icon_logo.png" width="300"/>
</p>

This is an **issue tracker** for Juno, an app running Jupyter locally on your iOS device (currently only distributed via TestFlight).

<p align="center"><a href="https://testflight.apple.com/join/XRjYzgMU"><b>🚀 Install from TestFlight</b></a></p>

Please, report any requests or defects you encounter with Juno by [opening an issue](https://github.com/navoshta/Juno-Issue-Tracker/issues/new/choose) in this repo. Also, please report any modules or packages that you would like to be pre-installed. Don't forget to [search for existing issues](https://github.com/rationalmatter/Juno-Issue-Tracker/issues) first, in case someone else has reported your thing already. Please, _do not_ report issues with the [Juno client](https://juno.sh) here (i.e. the one available on the AppStore, the Jupyter client app).

### Reporting issues
Juno is currently in active development, so I expect quite a few things not to work — please, report anything you notice that doesn't feel right. There are a few things that will be implemented or fixed soon (no need to report those):

* Native file management (similar to Pages, Numbers, etc.)
* Associating notebook file type with Juno (e.g. opening notebooks from Files app)
* Syncing documents via iCloud
* Updating to Python 3.7
* Package management for pure Python modules

### Pre-installed packages
Juno currently ships with **Python 3.6.6** kernel and following packages pre-installed:
* NumPy 1.16.1
* Matplotlib 3.0.3

### Installing pure-Python modules
You can install your own pure-Python modules by copying them into `/site-packages` folder in Juno documents via iOS's Files app. You should then be able to import them in your notebooks.

<br>
<p align="center"><a href="https://github.com/navoshta/Juno-Issue-Tracker/issues/new/choose"><b>⚠️ Open a new issue</b></a></p>
