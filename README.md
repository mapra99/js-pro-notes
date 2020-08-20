# JS Pro Tips

# What does it mean to be a JS Pro?

The road to be a professional is hard, it's the famous jr-to-sr path. The reality is that you can get there.

- Language Knowledge
- IDE Knowledge
- Best Practices
- Have a toolbox
- Ethics and professionalism
- Experience

JavaScript, as other languages, has a set of fundamentals that are a must-be to start with them. Furthermore, there are non-fundamental topics that are a nice-to learn but not needed at the beginning. The non-fundamentals are great to understand how the technology works and stop believing it's just magic.

## JS Non-Fundamentals

- Promises (In a super pro way)
- Getters & Setters in Classes
- Proxies
- Generators
- JavaScript Engine
- Prototype Inheritance
- Event loop
- Design patterns

# Starting a project

## Initializing NPM

- Initialize the project. That is, create a `package.json` file with the project info (some metadata) and the dependencies manifest.

```shell
npm init -y
```

- Install a development server.

```shell
npm install -D live-server
```

In `package.json` file a script can be created to associate the live-server with some npm command.

```javascript
// package.json
// ...
"scripts": {
	"start": "live-server"
},
// ...
```

