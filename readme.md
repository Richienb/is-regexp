# is-regexp [![Build Status](https://travis-ci.org/sindresorhus/is-regexp.svg?branch=master)](https://travis-ci.org/sindresorhus/is-regexp)

> Check if a value is a regular expression


## Install

```
$ npm install is-regexp
```


## Usage

```js
const isRegexp = require('is-regexp');

isRegexp('unicorn');
//=> false

isRegexp(/unicorn/);
//=> true

isRegexp(new RegExp('unicorn'));
//=> true
```


## Related

- [is](https://github.com/sindresorhus/is) - Type check values


---

<div align="center">
	<b>
		<a href="https://tidelift.com/subscription/pkg/npm-is-regexp?utm_source=npm-is-regexp&utm_medium=referral&utm_campaign=readme">Get professional support for this package with a Tidelift subscription</a>
	</b>
	<br>
	<sub>
		Tidelift helps make open source sustainable for maintainers while giving companies<br>assurances about security, maintenance, and licensing for their dependencies.
	</sub>
</div>
