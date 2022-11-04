# BubbleTask 0.0.3<a name="mark0"></a>

***Configurable, visual task-planning tool that lives on your desktop background.***

- [About](#mark1)
	- [Installation](#mark2)
- [Changelog](#mark3)
	- [0.0.3](#mark4)
	- [0.0.2](#mark5)
	- [0.0.1](#mark6)

---

# About<a name="mark1"></a>[^](#mark0)

A task deadline visualization tool written in python / tkinter

### Installation<a name="mark2"></a>[^](#mark1)

Available on pip - `pip install bubble_task`

1. Windows only due to \*nix systems being inconsistent.1. Install [Python 3.10+](https://www.python.org/downloads/) and make sure to include `IDLE, pip, tcl/tk, and check "Add python 3.* to PATH"`
1. Reboot your computer
1. Open a command prompt
1. Type the following command to install with pip: `pip install bubble_task`
1. Create a folder where you want the application to run
1. Create a text file in the (In Explorer: "right-click->new->Text Document")
1. Rename that file to "BubbleTask.bat" (Without quotes)
1. Edit the batch file in notepad (or other plaintext editor) to contain the following text : `python -m BubbleTask`
1. Double-Click the bat file to launch the program
1. You can make another folder + bat file to create a new instance of the program (Eg a separate set of tasks)
# Changelog<a name="mark3"></a>[^](#mark0)

## 0.0.3<a name="mark4"></a>[^](#mark3)

Fix issue with generated config file.

## 0.0.2<a name="mark5"></a>[^](#mark3)

Fix bug with redraw timing value being passed to renderer as a string on new profiles / first launches.

## 0.0.1<a name="mark6"></a>[^](#mark3)

Push



Generated with [py_simple_readme](https://github.com/AndrewSpangler/py_simple_readme)