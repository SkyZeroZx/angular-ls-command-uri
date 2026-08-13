# Angular LS command URI PoC

This repo contains two minimal PoCs for command URI injection in the Angular Language Service TSDK approval warning.

Both PoCs create:

```text
angular-lscommand.txt
```

## run-selected-text

Uses:

```text
workbench.action.terminal.runSelectedText
```

Open `repro.html`, keep the cursor on the command line, and click the injected `Allow` link in the Angular LS warning.

## run-commands

Uses `runCommands` together with `terminal.sendSequence`.

Clicking the injected `Allow` link creates the same `angular-lscommand.txt` file.
