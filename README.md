A really simple `stack run`. No magic involved.
Simply read `*.cabal` and grab the first executable listed.
`stack build` is called before invoking `stack exec`.
Extra arguments can be passed directly to the program executed:
`stack run -- -a -b foo`

Install is easy, just put the script in your `PATH`.
