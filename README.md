### :ledger: react-doc

The goal of this is to easily create/display documentation for a react project. I have been messing with parsing the files but plan on switching to babylon. With a few more updates this should be ready to at least be considered an alpha. Right now it generates extremely basic documentation (that uses react) into a `react-doc` directory within your project

This is an active (but early) WIP, to play around with it right now you would need to...

- `git clone git@github.com:bbohen/react-doc.git`
- `cd react-doc`
- `npm link`
- `react-doc` in your react project directory

By default react-doc will ignore `.git, node_modules & the resulting react-doc folder itself` if you want to ignore additional directories you can pass the `ignore` param

Example: `react-doc --ignore /someDirectory ` or `react-doc --i /someDirectory /someOtherDirectory`

Run tests using Jest:

- `npm run test`
