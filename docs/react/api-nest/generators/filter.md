# filter

Run the `filter` NestJS generator with Nx project support.

## Usage

```bash
nx generate filter ...
```

By default, Nx will search for `filter` in the default collection provisioned in `workspace.json`.

You can specify the collection explicitly as follows:

```bash
nx g @nrwl/nest:filter ...
```

Show what will be generated without writing to disk:

```bash
nx g filter ... --dry-run
```

## Options

### directory

Alias(es): d,path

Type: `string`

Directory where the generated files are placed.

### flat

Default: `true`

Type: `boolean`

Flag to indicate if a directory is created.

### language

Type: `string`

Possible values: `js`, `ts`

Nest filter language.

### name

Type: `string`

The name of the filter.

### project

Alias(es): p

Type: `string`

The Nest project to target.

### skipFormat

Default: `false`

Type: `boolean`

Skip formatting files.

### unitTestRunner

Default: `jest`

Type: `string`

Possible values: `jest`, `none`

Test runner to use for unit tests.
