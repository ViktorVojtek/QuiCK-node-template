# This is a _QuiCK node template_

As from the title of this project implies, this is just a simple nodejs server template to serve static files.
This project comes with some default folder structure and some basic files in `./public` direcotory, just for you to see it works.

## Usage

1. First install dependencies:

`yarn` or `npm install`

2. then run the development server with the following command:

`yarn dev` or `npm run dev`.

> All your static files should be located in `./public` directory

3. For running in production:

`yarn production` or `npm run production`

> This projects use [forever](https://github.com/foreverjs/forever#readme) CLI for continuous script run.
> Make sure you have it installed globaly or to use other modify the "production" script command in package.json file in the root of the project.

## License

[MIT](https://opensource.org/licenses/MIT)
