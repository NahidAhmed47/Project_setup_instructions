# Backend setup instructions


## Step 01
Open terminal:
```
mkdir my-backend-project
```
```
cd my-backend-project
```

## Step 02
```
npm init -y
```

## Step 03
```
npm install express mongoose dotenv cors zod
```

## Step 04
* Setup typescript
```
npm i -D typescript @types/express @types/node
```

## Step 05
* Generating tsconfig.json
```
npx tsc --init
```

## Step 06
* Set outDir 
```
{
  "compilerOptions": {
    ...
    "outDir": "./dist"
    ...
  }
}
```
* Set rootDir 
```
{
  "compilerOptions": {
    ...
     "rootDir": "./src" /* Specify the root folder within your source files. */,
    ...
  }
}
```