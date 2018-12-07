# less-plugin-keys

A Less plugin defining a utility function `keys()` for getting the properties of
a ruleset as a list, for easier iteration with
[`each()`](http://lesscss.org/functions/#list-functions-each).

## Up and Running

Install with npm: `npm install --save-dev less-plugin-keys`

To use it, either pass `--keys` to lessc when you build, or reference the plugin
with [`@plugin`](http://lesscss.org/features/#plugin-atrules-feature), like
this:

```@plugin "keys";```

## Limitations

I've only tested this function with rulesets as variables.  It's enough to get
by, but there's probably lots of opportunity for improvements.

## Contributing

This project is young, but you can help it grow up!  Issues and pull requests
are welcome.  Be kind and respectful.
