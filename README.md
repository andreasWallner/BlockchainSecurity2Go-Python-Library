# Blockchain Security2GO Starterkit library

__Warning:__ Still heavy WIP, all APIs may be subject to change!

The package provides basic functions to communicate with the
Infineon Blockchain Security2GO Starterkit cards.
It abstracts all of the commands available with the starterkit
with some simple functions.

## Using

To use from the IFX network just install the package via pip

    > pip install git+https://bitbucket.vih.infineon.com/scm/~wallnean/python-blockchain2go.git

This will install the library, which can be imported as `blockchain2go`.
In addition the `bc2go` command will be installed which can be used to communicate
with the card from the command line.

## Testing

To develop/test, it's best to use virtualenv. It allows for installing packages
in a "private" environment (for details see https://virtualenv.pypa.io/en/latest/)

    > virtualenv venv
    > source ./venv/Scripts/activate
    > pip install --editable .

