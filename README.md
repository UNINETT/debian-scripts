# debian-scripts
Scripts that help keeping debian based systems tidy.

* etc-update - list all .dpkg* files in /etc and offer to update them interactively, loosely based on gentoo tool with same name.
* dpkg-purge - list all installed packages that are marked for removal (removed by apt) and offers to purge them.
* apt-orphans - list all installed packages that lacks origin in apt repos, for example old packages after an upgrade, or packages installed directly with dpkg manually.
* apt-cuckoos - list all installed packages that are of a different version than what is available in the apt repos.
* apt-origin - list all installed packages from a repo matching patterns given as argument, specify no argument for help and examples.
