# Dine CPH readme

## Prerequisites

You will need:

1. An idea of how to set up a [Next.js](https://nextjs.org/) web-app.
2. An API key to use Google Maps + Geocode (see [Maps documentation](https://developers.google.com/maps/documentation/javascript/tutorial)).
3. An Airtable base with the same form fields as are used on the map and list pages. You'll need an API key + a base key (the ID of your Airtable base) as well.

## Setup

1. Run `npm install` (or `yarn`).
2. Copy the template file `.env.example` to `.env` and populate with keys from earlier.
3. Done.

## Development

Run `npm run dev` (or `yarn dev`) to start the development loop.

## Development

The Copenhagen project is deployed with [Zeit Now](https://zeit.co/home), utilising [Now Secrets](https://zeit.co/docs/v2/build-step#using-environment-variables-and-secrets) (see now.json file), but could be deployed wherever.
