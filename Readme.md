## Color Print (cprint) ##
Command line tool and function written in bash to print colorful text and styles.

## Requirements ##

+ Linux or Mac operating system
+ printf binary in path
+ Optional: figlet binary in path
+ Optional: cowsay binary in path

## Options ##
		-h
		[-v] -T
		[-v] [-E] [-n] [-p] [-I] [-b color] [-f color|-K|-R|-G|-Y|-B|-P|-C|-W|-Z|-z] [-L logfile] [-l logfile] -S STRING
		[-v] [-E] [-n] [-p] [-I] [-A|-F]  [-b color] [-f color|-K|-R|-G|-Y|-B|-P|-C|-W|-Z] [-L logfile] [-l logfile] -S STRING
		[-v] [-E] [-n] [-p] [-I] [-c] [-b color] [-f color|-K|-R|-G|-Y|-B|-P|-C|-W|-Z] [-L logfile] [-l logfile] -S STRING
		[-v] -e filename

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
		-L logfile: Output to specified log file with styles.
		-l logfile: Output to specified log file without any styles.
		-e filename: Export portable cprint bash function to specified file. Warning, this will overwrite specified file.
		-S string: Set the print string.
