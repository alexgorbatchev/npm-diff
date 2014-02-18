# npm-diff(1)

[![NPM version](https://badge.fury.io/js/npm-diff.png)](http://badge.fury.io/js/npm-diff)
[![Dependency status](https://david-dm.org/alexgorbatchev/npm-diff.png)](https://david-dm.org/alexgorbatchev/npm-diff)
[![devDependency Status](https://david-dm.org/alexgorbatchev/npm-diff/dev-status.png)](https://david-dm.org/alexgorbatchev/npm-diff#info=devDependencies)

[![NPM](https://nodei.co/npm/npm-diff.png?downloads=true)](https://npmjs.org/package/npm-diff)

  Diff two versions of a node module.

  ![screenshot](https://i.cloudup.com/RgiBccKvdt.png)

## Installation

```bash
npm install npm-diff
```

## Usage

```bash
$ npm-diff
Usage: npm-diff <module> <versionA> <versionB>
```

  __npm-diff(1)__ outputs regular __diff(1)__ content so it plays nice with other tooling.

## Tips

  Page big diffs:

```bash
$ npm-diff intersect 0.0.0 0.1.0 | less
```

  Pipe to [colordiff](http://www.colordiff.org) for colored git like diffs:

```bash
$ npm-diff intersect 0.0.0 0.1.0 | colordiff | less -R
```

## License

  MIT

