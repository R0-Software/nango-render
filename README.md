## tl;dr
This is a blueprint for Render.com to create a public [Nango](https://nango.dev) web service with a username/password. This template expects you to have an environment group title "Nango" and an environment varirable `NANGO_ENCRYPTION_KEY`. This key needs to be a 32 byte base64 encoded string. You can also update these variable names in the render.yaml file.

Deploy Nango with Render:

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy?repo=https://github.com/R0-Software/nango-render)