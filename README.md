# linux_fonts


cp -a fonts/ /usr/share/fonts/own-fonts
cd /usr/share/fonts/own-fonts
mkfontsdir && mkfontsscale
sudo fc-cache -fv
