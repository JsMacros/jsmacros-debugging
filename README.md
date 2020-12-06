# JsMacros debugging

# Setup

1. put an `"inspect": "port"` key in `.minecraft/config/jsMacros/options.json` 's `"extraJsOptions"` field.
1. change `port` to the port number you want to debug on.
1. ...
1. profit

note: All scripts will pause and require a debugger to be attatched and unpaused to do anything. They will log the URL for the debugger to console.
you can change the pausing behavior via the `inspect.WaitAttached` and `inspect.Suspend` options.

for more info see: https://www.graalvm.org/tools/chrome-debugger/


## License
GPL-2.0
