# Doc for timve

## setup/install plan
install
should put executable in usr/local/bin for all users
    -but might everything in ~./timve
        -ve's
        -ve templates
        -trash
        -logs(history/error)
        -editor files
        -config
        -readme
        -executable

## Options on Create:
```
1. Make new virtual environment
2. Make new project folder
3. Copy a default directory of files to the project folder
4. Make editor project files
    (ex:sublime text project/workspace files)
5. Make git repo and commit.
```

## manifest
```
Directories
base:               "~/.timve/"
virtual envs:       "~/.timve/venvs/"
projects:           "~/.timve/projects/"
                    "~/Projects/Python3/"   #likely to be elsewhere
project templates:  "~/.timve/templates/"   #todo: pick template
editor configs:     "~/.timve/editor/"
trash:              "~/.timve/trash/"

hook the project folder


Files
script:         "~/.timve/timve"
script:         "~/.timve/timve.config"
history log:    "~/.timve/history.log"      #change to timve.log?
error log:      "~/.timve/errors.log"
readme:         "~/.timve/README.md"
```

## notes

x - make on create templates load more than one in sequence

x- new file: .timignore
    x- create in project folder on create() and update on rm, r, cpy
    x- changed to .plbox

will copy work with git files? do i need to re init instead for new copy

upgrade pip on create? give choice in cfg?
pip install --upgrade pi

make posix compliant?
might be too much work, at least get rid of common bashisms

rename files

rename variables


open editor on new??

limit log size?: https://serverfault.com/questions/277948/easy-way-to-limit-file-size-stdout-on-a-shell-script-level?utm_medium=organic&utm_source=google_rich_qa&utm_campaign=google_rich_qa



