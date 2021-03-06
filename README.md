react-resume 📄
==============

> Generate resumes using [React](https://github.com/facebook/react), [`puppeteer`](https://github.com/GoogleChrome/puppeteer), and [`styled-components`](https://github.com/styled-components/styled-components).

Inspired by: https://github.com/salomonelli/best-resume-ever

**HTML preview:** https://react-resume.netlify.com/

**PDF output:** [`examples/resume.pdf`](examples/resume.pdf)

## Included batteries:

- [`create-react-app`](https://github.com/facebookincubator/create-react-app)
    + React
    + babel
    + webpack
    + eslint
    + and other cool stuff that `create-react-app` provides.
- [`puppeteer`](https://github.com/GoogleChrome/puppeteer)
- [`styled-components`](https://github.com/styled-components/styled-components)

Usage
=====

1. Clone this repository: `git clone https://github.com/dashed/react-resume.git`

2. Run `yarn install` (or `npm install`)

3. Run `create-react-app` in development mode: `yarn start` (or `npm start`)

4. Open http://localhost:3000 to view it in the browser.

5. Edit `src/`

6. Export PDF: `yarn pdf` (or `npm run pdf`)

7. Generated resume is in: `out/resume.pdf`

License
=======

MIT.
