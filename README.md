
## Node.js and Express.js with --typescript


## Step 1 : Create a package.json file

```sh
 npm init -y
```
## Step 2 : express.js and .env installation

```sh
  npm i express dotenv
```

> create .env file and add ENVIRONMENT variables in .env file 
> Use them like process.env.PORT

## step 3 : Type Script installation

```sh
 npm i -D typescript @types/express @types/node
```

## step 4 : Create tsconfig.json

```sh
 npx tsc --init
```

## change out directory "outDir": "./dist" in tsconfig.json

## Nodemon installation

```sh
npm install --save-dev nodemon
```

Add script in package.json

```sh
 dev : "nodemon --exec ts-node {main file path(server.ts)}"
```


## run script

```sh
npm run dev
```
