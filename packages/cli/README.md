# brodevscope

A CLI for adding components to your project.

## Usage

Use the `init` command to initialize dependencies for a new project.

The `init` command installs dependencies, adds the `cn` util, configures `tailwind.config.js`, and CSS variables for the project.

```bash
npx brodevscope init
```

## add

Use the `add` command to add components to your project.

The `add` command adds a component to your project and installs all required dependencies.

```bash
npx brodevscope add [component]
```

### Example

```bash
npx brodevscope add alert-dialog
```

You can also run the command without any arguments to view a list of all available components:

```bash
npx brodevscope add
```

## Documentation

Visit http://brodevscope.vercel.app to view the documentation.

## License

Licensed under the [MIT license](https://github.com/shadcn/ui/blob/main/LICENSE.md).
