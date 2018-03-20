## Color Print (cprint) ##
Command line tool and function written in bash to print colorful text and styles.

## Requirements ##

+ Linux or Mac operating system
+ printf binary in path
+ Optional: figlet binary in path
+ Optional: cowsay binary in path

## Options ##
		[-h] [-T]
		[-v] [-E] [-n] [-p] [-I] [-b color] [-f color|-K|-R|-G|-Y|-B|-P|-C|-W|-Z|-z] -S STRING
		[-v] [-E] [-n] [-p] [-I] [-A|-F]  [-b color] [-f color|-K|-R|-G|-Y|-B|-P|-C|-W|-Z] -S STRING
		[-v] [-E] [-n] [-p] [-I] [-c] [-b color] [-f color|-K|-R|-G|-Y|-B|-P|-C|-W|-Z] -S STRING

		-h: Display this dialog
		-T: Run selftest.
		-v: Enable verbosity for debugging.
		-E: Send output to stderr instead of stdout (default)
		-n: Do not print newline.
		-p: Prepend newline.
		-I: Enable bold colors.
		-A: Pass text through cowsay (if it exists:/usr/local/bin/cowsay)
		-F: Pass text through figlet (if it exists:/usr/local/bin/figlet)
		-c: Center text.
		-b color: Set background.
		-f color: Set foreground.
			Accepted color names for -f and -b:  black red green yellow blue purple cyan white
		-K: Print Black text.
		-R: Print Red text.
		-G: Print Green text.
		-Y: Print Yellow text.
		-B: Print Blue text.
		-P: Print Purple text.
		-C: Print Cyan text.
		-W: Print White text.
		-Z: Select a random foreground color for entire text.
		-z: Rainbow effect. Warning: will eat tabs and newlines.
		-S string: Set the print string.

## About Files in this repo ##
+ `cprint`: This is the fully featured binary with all listed options above. As long as you meet the system requirements, this should work out of the box. Try running `./cprint -T` to run the selftests to check.
+ `cprint_full_function`: This the fully featured version of cprint that can be copied and pasted into other bash scripts.
+ Just copy the entire function "print(){ ... }" into another bash script and you can reference it with the same command line flags.
