# typescript-npm-boilerplate

This is a boilerplate for a TypeScript 2.x NPM module.

## Usage

```
git clone https://github.com/zoyi/typescript-npm-boilerplate.git
mv typescript-npm-boilerplate your-project
cd your-project
// fix project name and version in package.json
npm install
typings install
```

## Testing

Uses Mocha, just do it!

```
npm test
```

## Building

Use TypeScript straight up

```
rm -rf lib && tsc -p .
```

or a convenience shortcut

```
npm run build
```

## Publishing

```
// Create a user on the npm registry
npm adduser

// Login to npm
npm login

// Your first publish
npm publish

// Update your publish
npm version patch
npm publish
```

## License

MIT
