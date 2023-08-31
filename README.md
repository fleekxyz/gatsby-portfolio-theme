# Gatsby Portfolio + Fleek template

![image](https://github.com/fleekxyz/gatsby-portfolio-theme/assets/55561695/b255ed67-ab94-4250-a30c-41f3f2f07f71)

This template uses [gatsby-theme-portfolio-minimal](https://github.com/konstantinmuenster/gatsby-theme-portfolio-minimal) made by [konstantin.digital](https://konstantin.digital).

## 🚀 Project Structure

```
/
├── content/
│   └── articles/
│   └── images/
│   └── sections/
│   └── settings.json
├── src/
│   └── pages/
├── static/
├── gatsby-config.js
└── package.json
```

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                | Action                                           |
| :--------------------- | :----------------------------------------------- |
| `yarn install`         | Installs the project dependencies      |
| `yarn run develop`         | Starts local dev server at `localhost:3001`      |
| `yarn run build`       | Build your production site to `./public/`           |
| `yarn run serve`       | Preview your build locally, before deploying     |
| `yarn run clean`        |  Deletes the `.cache` and `public` directories |

## ⚡ How to deploy to Fleek

### 1. Create a `fleek.json` config file:
You can configure this site deployment using [Fleek CLI]() and running:
```
 > fleek sites init
   WARN! Fleek CLI is in beta phase, use it under your own responsibility
    ? Choose one of the existing sites or create a new one. › 
    ❯ Create a new site
```
It will prompt you for a `name`, `dist` directory location & `build command`

- `name`: How you want to name the site
- `dist`: The output directory where the site is located, for this template it's `public`
- `build command`: Command to build your site, this will be used to deploy the latest version either by CLI or Github Actions

### 2. Deploy the site
After configuiring your `fleek.json` file, you can deployt the site by running

```
fleek sites deploy
```

After running it you will get an output like this:

```
 WARN! Fleek CLI is in beta, use it at your own discretion
   > Success! Deployed!
   > Site IPFS CID: QmP1nDyoHqSrRabwUSrxRV3DJqiKH7b9t1tpLcr1NTkm1M

   > You can visit through the gateway:
   > https://ipfs.io/ipfs/QmP1nDyoHqSrRabwUSrxRV3DJqiKH7b9t1tpLcr1NTkm1M
```

### Extra features
 - **Continuous Integration (CI):** `fleek sites ci` [Documentation.](https://docs.fleek.xyz/services/sites/#continuous-integration-ci)
 - **Adding custom domains:** `fleek domains create` [Documentation.](https://docs.fleek.xyz/services/domains/)


## 👀 Want to learn more?

Feel free to check [Gatsby documentation](://www.gatsbyjs.com/docs/).
