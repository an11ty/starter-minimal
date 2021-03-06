# Starter Site

This is an absolutely minimal starter for a website built
using [an11ty](https://github.com/an11ty/an11ty).

For a more complete starter, you should look at the official
[an11ty starter](https://github.com/an11ty/starter) pack.

## Setup

If you are starting from scratch, you can create a copy with
no bindings to this git repository using:

```bash
npx degit an11ty/starter-minimal my-website
cd my-website
git init
npm install
```

## Build

Build all pages and assets using:

```bash
npm run build
```

## Develop

Same as building, but updates pages and assets when file changes are detected,
and launches a [local HTTP server on port `8080`](http://localhost:8080):

```bash
npm run dev
```

## Folder Structure

This website uses the
[an11ty/template-minimal](https://github.com/an11ty/template-minimal),
which does not have very many options.

### `/`

The root folder of this project will not be built, so it typically
contains documentation or other non-public assets.

### `/site`

This folder contains all the site pages, articles, images, styles, etc.

Although not everything in it will be copied or merged into the final
site, it is safest to consider everything in it as "public" since it
may accidentally be copied over and accessible from your published website.

### `/site/_data`

This folder holds data that is then accessible inside templates. It has
a file [metadata.js](./site/_data/metadata.js) that has the site name and
other significant details.

## Contributing

Please file any issues or start discussions for this starter project
over in the [an11ty issues](https://github.com/an11ty/an11ty).

## License

This starter project published and released under the
[Very Open License](http://veryopenlicense.com), which
is a type of "public domain" license. Attribution is
always appreciated, but it means you are free to remove
this license and any reference to this project, for example
in a business or personal website.
