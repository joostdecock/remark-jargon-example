# An example repository for how to use remark-jargon

## About

[remark-jargon](https://github.com/freesewing/freesewing/tree/develop/packages/remark-jargon) is
a plugin for [the remark markdown processor](https://remark.js.org/).

This repository holds a very minimal example of how to use the plugin.

## Usage

Clone this repository. Then install dependencies with:

```bash
npm install
```

Then you can run the example with:

```bash
node index.js
```

Which will output the generated HTML for this line:

```md
This is a plugin for _remark_ originally written for _freesewing_.
```

It will inject the definitions for the terms `remark` and `freesewing` based on the contents of `jargon.js`.

## More info

Please refer to [remark-jargon](https://github.com/freesewing/freesewing/tree/develop/packages/remark-jargon) for
more information, including how to install and configure this plugin.

