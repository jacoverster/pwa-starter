# PWA Starter

A starter template for a Progressive Web App (PWA).

### References

- [Progressive Web Apps in 100 Seconds](https://www.youtube.com/watch?v=sFsRylCQblw)
- [Web.dev](https://web.dev/progressive-web-apps/)
- [Workbox](https://developers.google.com/web/tools/workbox)

### Icons

Create `logo.png` and generate the `icons` folder using [pwa-asset-generator](https://www.npmjs.com/package/pwa-asset-generator)

```bash
npx pwa-asset-generator logo.png icons
```

Copy the generated JSON output into `manifest.json`.

### Auditing

```bash
npx serve
```

Open Chrome DevTools -> Lighthouse -> Generate report
