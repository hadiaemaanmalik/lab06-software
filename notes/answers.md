apt update only downloads the latest list of available packages from the repositories. It does not install anything.
apt upgrade installs the newer versions of the packages that are already on my server.
So update always comes first, so that apt knows what is new, and then upgrade uses that list.
It is like checking the Play Store for updates first and then pressing "Update all".
