# bathelp

A simple wrapper around bash builtins, -h, and --help that adds the bat colorized output without addition piping at the commandline.

> _USAGE:_ bathelp <command>

All that happens are;
- test for bash builtins.
- test for --help.
- test for -h.
- give-up.

Whichever comes first is what is piped through to bat using the "--plain -l help" options.
