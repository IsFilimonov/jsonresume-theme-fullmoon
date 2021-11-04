# Full moon theme for JSONResume

A fullmoon template for JSON resume based on a [StackOverflow](https://github.com/phoinixi/jsonresume-theme-stackoverflow) theme.


## Installation

TODO: Describe the installation process


## Usage

TODO: how to use


## Publish
- Create a document in the root directory:
```bash
echo "//registry.npmjs.org/:_authToken=\n//npm.pkg.github.com/:_authToken=" > .npmrc
```
- Fill access tokens for GitHub and NMP;
- `npm publish` in the root.



## Differences
### Added
- Added a work contributions block `basics->location->conditions`:
  - `remote`: the possibility of working remotely;
  - `relocate`: relocation consent;
  - `businessTrips`: business trips consent;
  - `permits`: work permit in other countries. Must be completed if additional visas or cards are available.
```json
{
  "basics": {
    "location": {
      "conditions": {
        "remote": true,
        "relocate": true,
        "businessTrips": false,
        "permits": [
          "RU", "GE"
        ]
      }
    }
  }
}
```

### CSS changed
- Name and surname are bold:
```css
#header h1.name {
  font-weight: 700;
}
```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D


## History

TODO: Write history


## Credits

TODO: Write credits


##License

[MIT license](https://github.com/IsFilimonov/jsonresume-theme-fullmoon/blob/main/LICENSE)