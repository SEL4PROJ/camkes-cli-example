Example CAmkES CLI Project
==========================

This is a simple Hello World CAmkES project that demonstrates the CAmkES CLI.
There's no repo manifest, and no seL4 build system - just the application, and a
`camkes.toml` file telling the CLI how to build the project.

## Let's do this!

You will need:
 - the CAmkES CLI: `pip install camkes-cli`
 - CAmkES build deps: https://github.com/SEL4PROJ/camkes-cli-example.git

Now just clone, init and run:
```
git clone https://github.com/sel4proj/camkes-cli-example.git
cd camkes-cli-example
camkes-cli init
camkes-cli run x86
```

More info: https://wiki.sel4.systems/CAmkESCLI
