# Javascript describe snippets for Sublime Text 3


## Mac OS X

Install:

```bash
./installMac
# snippets will be copied to `~/Library/Application Support/Sublime Text 3/Packages/User/describe`
```

Uninstall:

```bash
./uninstallMac
```

## Ubuntu

Install:

```bash
./installUbuntu
# snippets will be copied to `~/.config/sublime-text-3/Packages/User/describe`
```

Uninstall:

```bash
./uninstallUbuntu
```


For other platforms:

```bash
# Install
cp -r ./*.sublime-snippet ~/.Sublime\ Text\ 3/Packages/User/describe

# Remove
rm -rf ~/.Sublime\ Text\ 3/Packages/User/describe
```

## Describe

Trigger: `describe` <br/>
Tab switch: 1 <br/>
Template: `1:Description` <br/>
Result: <br/>

```js
describe('Description', () => {
  // body
});
```

## It

Trigger: `it` <br/>
Tab switch: 1 <br/>
Template: `1:Name` <br/>
Result: <br/>

```js
it('Name', () => {
  // body
});
```