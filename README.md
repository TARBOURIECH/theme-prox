
## Installation 
The installation is done via the CLI utility. Run the following commands on the PVE node serving the Web UI:

```
~# wget https://raw.githubusercontent.com/TARBOURIECH/theme-prox/master/PVEDiscordDark.sh
~# bash PVEDiscordDark.sh install
```
Or this oneliner
```
bash <(curl -s https://raw.githubusercontent.com/TARBOURIECH/theme-prox/master/PVEDiscordDark.sh ) install
```


## Uninstallation
 To uninstall the theme, simply run the utility with the `uninstall` command.
 
## Installer & Security
The new installer relies on the `/meta/supported` and `/meta/imagelist` files being present in the repository. It also includes a silent mode. Run `bash PVEDiscordDark.sh -h` for usage instructions. 

Furthermore, you will be able to provide the environment variables `REPO` and `TAG` to specify from what repository and from what commit tag to install the theme from.   
`REPO` is in format `Username/Repository` and defaults to `Weilbyte/PVEDiscordDark` (this repository).    
`TAG` defaults to `master`, but it is strongly recommended to use the SHA-1 commit hash for security.

## Notes
Thanks to [jonasled](https://github.com/jonasled) for helping out with the old version, and thanks to [SmallEngineMechanic](https://github.com/smallenginemechanic) for catching bugs for the rewrite!

*Awoo'ing on this repo is encouraged.*
