# stylus-example

Example project showing how stylelint can be used to lint Stylus files.

## Getting Started

```bash
npm install
```

## Testing in VS Code

1. Install [stylelint by Shinnosuke Watanabe](https://marketplace.visualstudio.com/items?itemName=shinnn.stylelint)
2. Edit `~/.vscode/extensions/shinnn.stylelint-0.43.0/package.json`
	- In `activationEvents`, add `"onLanguage:stylus",` ([see example](https://github.com/tannerhodges/vscode-stylelint/blob/39febe2225dfec149bf20c2c8546bf19e2766802/package.json#L43))
3. Reload VS Code
4. Open `test.styl` and view linting errors

## References

For more information, see https://github.com/shinnn/vscode-stylelint/pull/245
