<img src="https://cdn.rawgit.com/oh-my-fish/oh-my-fish/e4f1c2e0219a17e2c748b824004c8d0b38055c16/docs/logo.svg" align="left" width="192px" height="192px"/>
<img align="left" width="0" height="192px" hspace="10"/>

#### plugin-bak

> Helps you instantly backup and restore files

[![MIT License][license-badge]](/LICENSE)
[![Fish Shell Version][fish-version-badge]][fish-shell-link]
[![Oh My Fish Framework][omf-badge]][omf-link]

<br/><br/><br/>

## Installation

    omf install bak

## Usage

- `cpbak <filename>`
- `mvbak <filename>`
- `uncpbak <filename>`
- `unmvbak <filename>`

## Example

```
⋊> ~/tmp touch test.txt
⋊> ~/tmp ls
test.txt
⋊> ~/tmp cpbak test.txt
⋊> ~/tmp ls
test.txt    test.txt.20230829_100153.bak
⋊> ~/tmp
```

## License

[MIT][mit] © [Bruno Ferreira Pinto][author] et [al][contributors]

[license-badge]: https://img.shields.io/badge/license-MIT-007EC7.svg?style=flat-square
[fish-version-badge]: https://img.shields.io/badge/fish-v2.2.0%2B-007EC7.svg?style=flat-square
[fish-shell-link]: https://fishshell.com
[omf-badge]: https://img.shields.io/badge/Oh%20My%20Fish-Framework-007EC7.svg?style=flat-square
[omf-link]: https://www.github.com/oh-my-fish/oh-my-fish
[mit]: http://opensource.org/licenses/MIT
[author]: http://github.com/bpinto
[contributors]: https://github.com/oh-my-fish/plugin-z/graphs/contributors
