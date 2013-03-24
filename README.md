ewebkit-debian
==============

ewebkit-debian is to create deb package for ewebkit and ewebkit2

For ewebkit
# move to ewebkit folder
cd ewebkit
# link webkit folder as webkit-efl
ln -s /your/webkit/folder webkit-efl
# generate package
dpkg-buildpackage -rfakeroot -uc -b
