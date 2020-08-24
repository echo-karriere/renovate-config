# renovate-config

Renovate configuration for the projects in the echo karriere organization, use
these for all projects where we want automatic updates of dependencies etc.

## Usage

The default is a nice base for everything, you can safely use this for all
projects.

```json
{
  "extends": ["github>echo-karriere/renovate-config:default"]
}
```

For web applications written in React etc, use the `webapp` configuration:

```json
{
  "extends": ["github>echo-karriere/renovate-config:webapp"]
}
```
