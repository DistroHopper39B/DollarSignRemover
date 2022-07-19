# DollarSignRemover
Have you ever copy-pasted a chunk of code from the internet and had it fail to execute because of the dollar signs at the beginning of each line (to symbolize that you are to run the code as normal user and not as root)? Well, then DollarSignRemover is for you. This program works on any version of Linux, BSD, Unix, Mac OS X, you name it- as long as it isn't Windoze. (Well, on Windows, it will work using any shell interpreter such as Git for Windows, Cygwin, or WSL.)

To install, simply download the `$` file and place it in a directory in your `$PATH` (/usr/local/bin or ~/.local/bin are probably in your PATH, but you can check by typing "echo $PATH" in your terminal). Then, when you copy-paste any code from the Internet, you won't get errors such as `-bash: $: command not found.`

**Note: I am not responsible if you copy-paste malicious code from the internet. Use common sense and make sure you understand what the code is doing. And don't copy paste anything that says `sudo rm -rf --no-preserve-root /` unless you hate all of your files on all of your hard drives.**

(If someone has already made this script, just know that we both had the same issue and came up with the same solution on our own. I did not steal this program from anyone else and neither did you. It's so simple we just had the same idea.)
