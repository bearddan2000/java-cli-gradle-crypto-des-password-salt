# java-cli-gradle-crypto-des-password-salt

## Description
A demo for DES encryption of a password.
DES is a 48 byte encryption. SALT is the
mixing of the original text with a secret key.
It is considered more secure to store the
SALT then the encrypted original text, however
this can still be cracked with rainbow tables.

## Tech stack
- gradle

## Docker stack
- gradle:jdk11

## To run
`sudo ./install.sh -u`

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
