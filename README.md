work in much progress

# Doc for planterbox

## Options on Create:
```
1. Make new virtual environment
2. Make new project folder
3. Copy a default directory, or templates to the project folder
4. Make editor project files
    (ex:sublime text project/workspace files)
5. Make git repo and commit.
6. Pip install reqs, and upgrade pip
```

## manifest
```
allow customization though config,
    ex) many may want their Projects folder seperate.
    - maybe can store most everything in a hidden dot directory
        - will be able to navigate to through ve commands??
            - is easy access through finder/explorer/normal cl even necc?

--still correct?
Directories:

    base:               "planterbox/"
    archives:           "planterbox/archives/"
    editor configs:     "planterbox/editor/"
    projects:           "planterbox/projects/"
                        "~/Projects/test_projects/"
    project templates:  "planterbox/templates/"                    
    requirements:       "planterbox/reqs/"
    trash:              "planterbox/trash/"
    virtual envs:       "planterbox/venvs/"

    hook the project folder? # what did i mean by this?

Files:

    script:         "planterbox/planterbox"
    utils script:   "planterbox/utils" #add back to main script?
    config script:  "planterbox/planterbox.cfg"
    history log:    "planterbox/history.log" #change to plbox.log?
    error log:      "planterbox/errors.log" #plerror.log? or keep generic?
    readme:         "planterbox/README.md"

```

## notes

## todo
x- make on create templates load more than one in sequence
x- new file: .timignore
    x- create in project folder on create() and update on rm, r, cpy
    x- changed to .plbox
x- upgrade pip on create? give choice in cfg?
    x- pip install --upgrade pi

## questions
- will copy work with git files? do i need to re init instead for new copy
- make more posix compliant?
- rename accordingly, standards
    - files
    - variables
- open editor on new??
    - subl command, what for atom, etc
- limit log size?: https://serverfault.com/questions/277948/easy-way-to-limit-file-size-stdout-on-a-shell-script-level?utm_medium=organic&utm_source=google_rich_qa&utm_campaign=google_rich_qa

- setup/install plan
    - create intall script to create all directories/place files
    - should put executable in usr/local/bin for all users? prob not, or dev
        + might be fitting that you can hacks script as you code/script

