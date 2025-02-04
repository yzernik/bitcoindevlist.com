# Bitcoin Donation Portal

## Support bitcoin developers so they can focus on building our future

[The website](https://bitcoindevlist.com/) lists people working on Bitcoin and related projects.
The goal is to increase the visibility of contributors to the space that are accepting donations.
If you are currently working on a bitcoin related open source project, submit a PR to get yourself added.

We do not want to be gatekeepers for additions.
As a baseline we have decided on a policy that requires at least one ACK for new entries.

## Adding yourself to the lists

If you are currently working on a bitcoin related open source project, submit a PR to [get yourself added](https://github.com/dennisreimann/bitcoindevlist.com/edit/master/donatees).
Just append your block of data to the bottom, the list is shuffled on page load.
You can use Markdown in the `description` property.

We also support [BOLT12](https://bolt12.org/) (`bolt12_single` and `bolt12_recurring`, [example](./donatees/sjors-provoost.json)) and [Lightning Address](https://lightningaddress.com/) (`lnaddr`, [example](./donatees/fitti.json))

## Local build

[Node.js](https://nodejs.org/en/) is a prerequisite, the dependencies are managed via npm.
Once you have cloned this repo, you can setup the packages:

```bash
npm install
```

Create a build and rebuild on file change:

```bash
npm start
```

This will bring up the dev server and pattern library on [localhost:3000](http://localhost:3000).
