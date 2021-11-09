# shopify-hydrogen

Hydrogen quickstart for Shopify themes

[Check out the docs](https://shopify.dev/custom-storefronts/hydrogen)

```
npx create-hydrogen-app
```

```
cd kamaboko-customizer
```

```
npm install
```

```
npm install --legacy-peer-deps
```

```
code .
```

Go to your dev store dashboard

> Apps
> Manage private apps
> Enable private app development
> Check everything
> Create private app
> Add App details (private app name and emergency developer email)
> Admin API Permissions (currently I have all on Read access -- I need to figure this out)
> Hit Save

shopify.config.js

```
export default {
  locale: 'en-us',
  storeDomain: 'hydrogen-preview.myshopify.com', //replace this with your storeDomain
  storefrontToken: '3b580e70970c4528da70c98e097c2fa0', //Storefront API access token
  graphqlApiVersion: 'unstable',
};
```

```
npm run dev
```
