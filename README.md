# HOPE SYSTEM Version1

<h1 align="center">hopesys-1</h1>

<p align="center">HOPE SYSTEM Version1 website</p>

<p align="center">https://hopesys.github.io/v1/</p>

<p align="center"><a href="https://waffle.io/chalermporn/v1">Waffle board</a></p>

<p align="center"><a href="https://circleci.com/gh/chalermporn/v1/tree/master"><img src="https://circleci.com/gh/chalermporn/v1/tree/master.svg?style=svg" alt="CircleCI" /></a></p>


## Folder structure

- `pages` [Next.js][] pages
- `static` [Next.js] static files
- `components` React components
- `public` Additional files to be copied to GitHub pages
- `resources` Additional files that may be used from JavaScript files (e.g. svg files)

[Next.js]: https://github.com/zeit/next.js

## Install the dependencies
```
yarn
```

## Running development server
```
yarn start
```

## Generating static web site
```
yarn run build
```

## Testing the web site
```
yarn run serve-static
```

Test the website at http://localhost:3002/

## Deployment
When a commit is added to `master` branch, it will be deployed to GitHub Pages by the CI.
