# Atom settings

## Installation
1. Fork the repo

2. Clone the repository, and add the ```bin/``` folder to your path as follows:

    ```
    git clone git@github.com:xxxx/atom_config ~/.atom_config
    export PATH=$PATH:~/.atom_config/bin
    ```

3. Add the path to your ~/.bash_profile

    ```
    echo "export PATH=$PATH:~/.atom_config/bin" >> ~/.bash_profile
    ```

## Working with

Copy the settings from your local repo to .atom

```
atom_config copy_to_atom
```

## Refreshing after making changes in atom

Copy all the setting files from .atom into your local repo

```
atom_config copy_from_atom
```

Commit and push these changes back to your github repo

```
atom_config push "commit message"
```
