# A little surveys app
A little web interface to manage surveys.

## Stack
- [Remix](https://remix.run/)
- [Remix Vite docs](https://remix.run/docs/en/main/future/vite) for details on supported features.

## Development

Run the Vite dev server:

```shellscript
npm run dev
```

## Deployment

First, build your app for production:

```shellscript
npm run build
```

Then run the app in production mode:

```shellscript
npm start
```
Now you'll need to pick a host to deploy it to.

### DIY

If you're familiar with deploying Node applications, the built-in Remix app server is production-ready.

Make sure to deploy the output of `npm run build`

- `build/server`
- `build/client`
