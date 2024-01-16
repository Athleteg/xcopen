# xcopen
This simple shell script helps you run your favorite project via the Xcode app in the fastest way.\
The main idea of it is entering a simple one command in the terminal for magic.

![](/Assets/Intro.png)

## Feature list:
- Running a project with one simple command in a terminal
- There is no need to always go into the project folder
- Keeps your favorite path to a project until you change or remove it
- Sets all necessary data for script automatically (env property and alias to `.zshrc` file)
- Highlights tips during the running of a script
- Supports multiple useful script options
- Maintenances a deleting of all script data simply with one command

## Installation:
1. Download this repo.
2. In the terminal change the directory on a script folder.
3. Set a permission (eg. `% chmod 500 xcopen`).
4. The first launch must be performed in the current shell environment with the (.) command\
	(eg. **`% . ./xcopen`** *OR* **`% source ./xcopen`**).
5. Choose 2nd option in the main menu of script.
6. Set a path with a project. Just enter it or find the project folder and use your mouse to move it to the terminal.
7. Magic. 
<img src="https://media.giphy.com/media/Z3VgQu8hkVeB1bakS9/giphy.gif" width="180" height="110"/>

## Usage:
All subsequent launches might be performed with a short global alias.\
Wherever you are in the terminal - just run a script with **`% xcopen`**.

If you are running a script without any options you will get the main menu of a script.

Besides, a script supports 6 options.

Use **`% xcopen -h`** to display the help menu where you will find all options with their meaning.

To run a project in the fastest way just enter **`% xcopen -1`** *(this option works only in case you set a path for a project).*

Also, a script sets an alias and a path you specified behind a script (automatically).\
All that is required from you is to set a path of a project via the 2nd option in the main menu of a script or with `% xcopen -2`.

You might check all actual script data with such options as `-a` for alias, -`e` for env:\
`% xcopen -a`, `% xcopen -e` OR combine them `% xcopen -ae`.

In case you would like to delete a script from your Mac - use `-d` option before.\
*(It implies that all script data will be removed from a `.zshrc` file.)*\
`% xcopen -d`.

> [!CAUTION]
> *(If you replace a script into another folder - run it from a new path as in the first launch via `(.)` or `source` command.\
>  The script automatically will change an alias path in the `.zshrc` file for the sake of usage of `% xcopen`.)*

## License:
[MIT license.](https://github.com/Athleteg/xcopen/blob/main/LICENSE)


## Bottom line:

If you are a bit lazy, then try to use it :)\
I hope it helps you to avoid your routine job.

In case of any questions, feedback, or suggestions, reach me by any comfy approach (see [profile](https://github.com/Athleteg))

Enjoy it :)
