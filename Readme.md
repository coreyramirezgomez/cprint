## Color Print (cprint) ##
Command line tool and function written in bash to print colorful text and styles.
## Requirements ##
+ Linux or Mac operating system
+ printf binary in path
+ Optional: figlet binary in path
+ Optional: cowsay binary in path
## Options ##
		-h: Display this dialog
		-f color: Set foreground.
		-b color: Set background.
			Accepted color names for -f and -b: black red green yellow blue purple cyan white
		-I: Enable bold.
		-c: Center text.
		-n: Do not print newline.
		-p: Prepend newline.
		-F: Pass text through figlet (if it exists:/usr/local/bin/figlet)
		-A: Pass text through cowsay (if it exists:/usr/local/bin/cowsay)
		-K: Print Black text.
		-R: Print Red text.
		-G: Print Green text.
		-Y: Print Yellow text.
		-B: Print Blue text.
		-P: Print Purple text.
		-C: Print Cyan text.
		-W: Print White text.
		-S string: Set the print string.
		-T: Run selftest.
		-v: Enable verbosity for debugging.
		-Z: Select a random foreground color for entire text.
		-z: Rainbow effect. Warning: will eat tabs and newlines.
## About Files in this repo ##
+ `cprint`: This is the fully featured binary with all listed options above. As long as you meet the system requirements, this should work out of the box. Try running `./cprint -T` to run the selftests to check.
+ `cprint_full_function`: This the fully featured version of cprint that can be copied and pasted into other bash scripts.
++ Just copy the entire function "print(){ ... }" into another bash script and you can reference it with the same command line flags.
+ `cprint_slim_function`: This is slimmed down version of cprint that can be copied and pasted into other bash scripts.
++ Just copy the entire function "print(){ ... }" into another bash script and you can reference it with the same command line flags.
