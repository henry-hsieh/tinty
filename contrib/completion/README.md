# Shell Completions

Run `tinty generate-completion <bash|elvish|fish|powershell|zsh>` to
generate a shell completion script for your shell of choice. Make sure
to source the generated script in your shell startup file (`*rc`).

The files in this directory are custom completion scripts which has been
optimised further than the standard completions `tinty` generates. These
scripts complete dynamic values (scheme names) as well as the standard
subcommands and flags. Currently `bash` is the completion which has been
optimised this way, the rest are the default completions generated by
`tinty generate-completion <shell_name>`.