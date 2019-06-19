## Cool Print (cprint) ##
Command line tool and function written in bash to print colorful text and styles.

## Requirements ##

+ Linux or Mac operating system
+ Optional: printf binary in path.
+ Optional: figlet binary in path.
+ Optional: cowsay binary in path.

## Options ##
		Usage for cprint:

		[-h|--help]: Display this dialog
		--debug: Enable debugging.
		--selftests: Run selftests.
		--export filename: Export portable cprint bash function to specified file.

		[-e|--stderr]: Send output to stderr instead of stdout (default)
		[-n|--no-newline]: Do not print newline.
		[-p|--pre-newline]: Prepend newline.
		[-I|-b|--bold]: Enable bold colors.
		[-A|--cowsay]: Output with cowsay.
		[-F|--figlet]: Output with figlet.
		--cow-file file: Set the cowsay style if using cowsay.
		--fig-file file: Set the figlet style if using figlet.
		[-c|--centered]: Center text.
		[--BG|--bg|--background] color-name: Set background color-name.
		[--FG|--fg|--foreground] color-name: Set foreground color-name.
		[Accepted color-names: black white red yellow green blue cyan purple random]

		[-K|--black]: Print Black text.
		[-W|--white]: Print White text.
		[-R|--red]: Print Red text.
		[-Y|--yellow]: Print Yellow text.
		[-G|--green]: Print Green text.
		[-B|--blue]: Print Blue text.
		[-C|--cyan]: Print Cyan text.
		[-P|--purple]: Print Purple text.
		[-Z|--random]: Print Random Color text.
		[-L|--log-styled] logfile: Output to specified log file with styles.
		[-l|--log] logfile: Output to specified log file without styles.
		[-S|--string] string: Set the print string.
