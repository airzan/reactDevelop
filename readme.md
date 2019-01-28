After downloading the repo, install the npm packages.

```
npm i
```

Then run the watcher to process the JSX flavoured JavaScript files in the `src/` folder.

```
npx babel --watch src --out-dir . --presets react-app/prod
```
