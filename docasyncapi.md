# Support AsyncAPI Initiative

Your support would be greatly appreciated for AsyncAPI, where we aim to improve the current state of Event-Driven Architectures (EDAs) and their tooling.

In order to support AsyncAPI, the following options are available -

- **Open Collective**: Visit our [Open Collective Page](https://opencollective.com/asyncapi)
- **GitHub Sponsors**: Visit our [GitHub Sponsors Page](https://github.com/sponsors/asyncapi)
- **Linux Foundation Crowdfunding**: Visit our [Linux Foundation Crowdfunding Page](https://crowdfunding.lfx.linuxfoundation.org/projects/445898e9-42a2-4965-9e0a-c2a714f381bc)


# How do we manage expenses?

1. AsyncAPI Initiative welcomes support in all 3 ways mentioned above.

2. In case of GitHub Sponsors, the fund is directly transferred to Open Collective.

3. Since Open Collective and Linux foundation Crowdfunding are totally disjoint, 
   thus we can conclude that we can conclude that we manage expensed in 2 platforms ->
   
   - Open Collective & GitHub Sponsors fundings on Open Collective
  
   - Linux Foundation Crowdfunding on the same 

## Run locally

1. Fork the repository by clicking on `Fork` option on top right of the main repository.

2. Open Command Prompt on your local computer.

3. Clone the forked repository by adding your own GitHub username in place of `<username>`.
   For multiple contributions it is recommended to have [proper configuration of forked repo](https://github.com/asyncapi/community/blob/master/git-workflow.md)

```bash
git clone https://github.com/<username>/website/
```

4. Check if NPM Package is already installed on your local computer

```bash
npm
```
   If it shows details details of the package then the NPM package is already installed. 
   Otherwise you can install [NPM Package](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)

3. Navigate to the website directory.

```bash
cd website
```

4. Install all website dependencies. 

```bash
npm install
```

5. Run the website locally

```bash
npm run dev
```
