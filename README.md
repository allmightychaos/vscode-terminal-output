# VSCode - Change Terminal Prompt (MacOS)

* Open the terminal in Visual Studio Code by going to the View menu and selecting "Terminal".
* In the terminal, type the following command and press Enter:

```
code ~/.zshrc
```
* If that does not work, you can try:

```
/Applications/Visual\ Studio\ Code.app/Contents/Resources/app/bin/code ~/.zshrc
```

* In the `~/.zshrc` file, scroll down to the bottom and add the following line:

```
PROMPT='> '
```

* Save the changes to the `~/.zshrc` file.
* Close the terminal and reopen it to apply the changes. You should now see the terminal prompt changed to "> ".

* Alternatively, you can also use the `echo` command to change the terminal prompt by appending the following line to the `~/.zshrc` file:

```
export PS1="> "
```

* To do this, you can follow these steps:

* Open the terminal in Visual Studio Code by going to the View menu and selecting "Terminal".
* In the terminal, type the following command and press Enter:

```
echo 'export PS1="> "' >> ~/.zshrc
```

* Close the terminal and reopen it to apply the changes. You should now see the terminal prompt changed to "> ".
