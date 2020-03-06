# jh
Command line tool to make directories and touch flag.txt/solution.txt in those directories.

## Installation
Run the following code to clone it, chmod it, and move it to your path.

```
git clone https://github.com/l1berate/jh
cd jh
chmod +x jh
sudo mv jh /usr/local/bin/
```

## Usage
Run the following with no arguments to create a flag.txt and solution.txt in the current directory. 
```
jh
```

Run the following to make a new directory. This will create a directory called '01_new_challenge' if it's the first time. Everytime after that it will keep increasing the first two digits, e.g. the next time will be 02_next_challenge.
```
jh new_ctf_challenge
```

Finally, run this when you're done with a challenge. This will attach a '_COMPLETE' to the pwd.
```
jh done
```

## Don't want colors?
Open up jh in your favorite text editor, and change the variable USE_COLORS to False so it looks like the code below.
```
#Change this to false if you'd rather not have colors.
USE_COLORS = False
```

## License
[MIT](https://choosealicense.com/licenses/mit/)
