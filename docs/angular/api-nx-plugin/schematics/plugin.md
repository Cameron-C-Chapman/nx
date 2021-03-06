# plugin

Create a Nx Plugin

## Usage

```bash
ng generate plugin ...
```

By default, Nx will search for `plugin` in the default collection provisioned in `angular.json`.

You can specify the collection explicitly as follows:

```bash
ng g @nrwl/nx-plugin:plugin ...
```

Show what will be generated without writing to disk:

```bash
ng g plugin ... --dry-run
```

### Examples

Generate libs/plugins/my-plugin:

```bash
ng g plugin my-plugin --directory=plugins
```

## Options

### directory

Alias(es): d

Type: `string`

A directory where the plugin is placed

### linter

Default: `tslint`

Type: `string`

Possible values: `eslint`, `tslint`

The tool to use for running lint checks.

### name

Type: `string`

Plugin name

### skipFormat

Default: `false`

Type: `boolean`

Skip formatting files

### skipTsConfig

Default: `false`

Type: `boolean`

Do not update tsconfig.json for development experience.

### tags

Alias(es): t

Type: `string`

Add tags to the library (used for linting)

### unitTestRunner

Default: `jest`

Type: `string`

Possible values: `jest`, `none`

Test runner to use for unit tests
