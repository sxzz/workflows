# sxzz/workflows

A collection of reusable GitHub Actions workflows and actions for TypeScript projects.

## Features

- Standardized CI/CD workflows for testing, building, and releasing
- Easy integration into any TypeScript repository
- Includes custom actions for setup and automation

## Included Workflows

- **Unit Test**: Runs tests and reports coverage
- **Release**: Publishes releases to npm/JSR
- **Auto Fix**: Automatically fixes code style issues
- **Publish Any Commit**: Releases any commit as a package

## Usage

To use a workflow, reference it in your project’s `.github/workflows/*.yml`:

```yaml
# Example: Unit Test
name: Unit Test
uses: sxzz/workflows/.github/workflows/unit-test.yml@main
```

See the [`examples/`](./examples) folder for sample workflow configurations:

- [Unit Test](./examples/unit-test.yml)
- [Release](./examples/release.yml)
- [Auto Fix](./examples/autofix.yml)
- [Publish Any Commit](./examples/release-commit.yml)

## Actions

- [`setup-js/action.yml`](./setup-js/action.yml): Sets up Node.js and installs dependencies

## Contributing

Contributions and suggestions are welcome! Please open issues or pull requests.

## Sponsors

<p align="center">
  <a href="https://cdn.jsdelivr.net/gh/sxzz/sponsors/sponsors.svg">
    <img src='https://cdn.jsdelivr.net/gh/sxzz/sponsors/sponsors.svg'/>
  </a>
</p>

## License

[MIT](./LICENSE) License © 2025-PRESENT [Kevin Deng](https://github.com/sxzz)
