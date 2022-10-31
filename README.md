# Espanso

This contains my personal espanso files.

## Documentation

- https://espanso.org/docs/get-started/

## Espanso Hub

https://hub.espanso.org/

## Don't autoload match

MAKE SURE TO INCLUDE THE UNDERSCORE!

As explained in the Organizing matches section, Espanso automatically loads all YAML files located in the match directory, except the ones starting with an \_ underscore.

`$CONFIG/match/_filename.yml`

## Packages

```sh
# List installed packages
espanso package list

# Show installation path
espanso path packages

# Install package
expanso install <package-name>

# Install specific version package
expanso install <package-name> --version <package-version>

# Uninstall package
espanso uninstall <package_name>

# Update package
espanso package update <package_name>

# Update all packages
espanso package update all



```

## Useful Tips

Install a package
`espanso install <package-name>`

Get path
`espanso path`

Quick edit configuration
`espanso edit`

Reload espanso
`espanso restart`

## Search Bar

Search bar: `ALT + SPACE`

Search bar then `>` to show available commands.

## Useful shortcuts

Search bar: `ALT + SPACE`
`toggle_key`: `ALT` - Toggle ON/OFF: double press `toggle_key`
