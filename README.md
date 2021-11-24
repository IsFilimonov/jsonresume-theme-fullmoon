<span class="jsonresume-theme-fullmoon-npmversion"><a href="https://npmjs.org/package/jsonresume-theme-fullmoon" title="View this project on NPM"><img src="https://img.shields.io/npm/v/jsonresume-theme-fullmoon.svg" alt="NPM version" /></a></span>

# Fullmoon theme for JSON Resume

A fullmoon template for [JSON Resume](https://jsonresume.org/) based on a [StackOverflow](https://github.com/phoinixi/jsonresume-theme-stackoverflow) theme.


## Get ready?
More [information](https://jsonresume.org/getting-started/) about JSON Resume start.

### Command Line Tool
Install JSON Resume Command Line Tool globally for **NPM**:
```bash
npm install -g resume-cli
```

Official [CLT repository](https://github.com/jsonresume/resume-cli) with all commands.


### Resume file
- Create `resume.json` file according a [schema](https://jsonresume.org/schema/).
- Hosting a file `https://registry.jsonresume.org/{your_github_username}` and choose a theme to set `{ "meta": { "theme": "elegant" } }`. 

*Note*: a theme must be official register (check [dependencies](https://github.com/jsonresume/registry-functions/blob/master/functions/package.json)).


## Usage

- Start local server from folder where the `resume.json` puts:
```bash
resume serve
```

- If a theme is officially register you can change a render:
```bash
resume serve --theme <theme name>
```

- If you have you own theme locally, just put a `resume.json` to the root folder:
```bash
resume serve --theme .
```

## TODO
- [ ] A `certificates` block.
- [ ] `basics.location.conditions.permits`: work permit in other countries. Must be completed if additional visas or cards are available.
- [ ] A Fullmoon-min (one page) theme for export CV in pdf and attach to the html version by a link.


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D


## History

I plan to document all the history of changes in the releases.


## Credits
Thanks [Francesco Esposito](https://francesco.netlify.com/) for a great [Stack Overflow](https://github.com/phoinixi/jsonresume-theme-stackoverflow) theme!

If you find them useful, give them ⭐a star and enjoy.


## License

[MIT license](https://github.com/IsFilimonov/jsonresume-theme-fullmoon/blob/main/LICENSE)