### Installation and usage

Install the package globally in your machine:
```
npm i -g Bannerwise/cz-jira-smart-commit#master
```

On the repo you wanna commit, create a file `.cz.json` with the following content:
```
{
  "path": "/Users/irotnes/.nvm/versions/node/v15.5.0/lib/node_modules/cz-jira-smart-commit"
}
```
Replace `irotnes` with your user and make sure you are pointing to the correct installation folder (check your node version!)

Once that's done, you can commit to a repo by running `git cz` in the project root.


