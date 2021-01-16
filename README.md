# local-php-security-checker AUR Package
[![Build Status](https://travis-ci.com/famoser/local-php-security-checker-aur.svg?branch=master)](https://travis-ci.com/famoser/local-php-security-checker)

## Update package

0. Get newest version from https://github.com/fabpot/local-php-security-checker
1. Update package version in PKGBUILD
2. Execute `update.sh`

or 

3. Generate new checksums with `updpkgsums`
4. Test install `makepkg -si`
5. Update .SRCINFO `makepkg --printsrcinfo > .SRCINFO`
6. `git remote add arch ssh://aur@aur.archlinux.org/local-php-security-checker-cli.git`
7. `git push arch`
