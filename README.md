# HUB Landing Page using Strapi API

## Project created to management the creation of Landing Pages using Next JS and Strapi.

## Repo Image

- Cloudinary to save images
- Configuring cloudinary in stripe https://www.npmjs.com/package/@strapi/provider-upload-cloudinary

## Repo Database

- ElephantSQL to the database (configure during the start project)

### Install dependences

`npm install ` or `yarn install`

### Starting the project

`npm run dev`

### In the .env.example you'll find the keys necessary to run the project.

### Dynamic Zones

To see all level of data you have to install a plugin and change de url to populate de data.

`npm install strapi-plugin-populate-deep`

and int the url use like below:

`http://localhost:1337/api/pages?populate=deep`
