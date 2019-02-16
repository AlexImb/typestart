# Typestart

Typestart is a web/DOM library starter with these features:

[![Travis CI](https://img.shields.io/travis/AnandChowdhary/typestart.svg)](https://travis-ci.org/AnandChowdhary/typestart)
[![Minzipped size](https://img.shields.io/bundlephobia/minzip/typestart.svg)](https://www.npmjs.com/package/typestart)
[![GitHub](https://img.shields.io/github/license/anandchowdhary/typestart.svg)](https://github.com/AnandChowdhary/add-to-calendar/blob/master/LICENSE)
![Vulnerabilities](https://img.shields.io/snyk/vulnerabilities/github/AnandChowdhary/typestart.svg)

- Written in Typescript
- Built-in demo with GitHub pages (`./docs/` folder)
- main/module/types in `package.json`
- Bundled as UMD (works as a module)
- Exposes `window.Library` (works with CDNs)
- Test with Jest
- Build with Travis CI
- Clean with Prettier

## Getting started

Clone and start your project:

```bash
git clone git@github.com:AnandChowdhary/typestart
cd typestart && git init
```

Find and replace "typestart" with your library name and "AnandChowdhary" with your GitHub username.

### GitHub configuration

Setup GitHub Pages demo by going to Settings → GitHub Pages → Source → master branch /docs folder.

### Development

Start development server with HMR:

```bash
yarn start
```

In a separate terminal, start Prettier:

```bash
yarn prettier-watch
```

### Production

Build a production verion:

```bash
yarn build
```

## Why another starter?

I've used a bunch of different Typescript library starters, but they all have tons of boilterplate (super long build rules, scripts for releases, publishing, building, etc.) 

Typestart is—like the name suggests—a starting point.

## License

Unlicense (public domain, do whatever you want)
