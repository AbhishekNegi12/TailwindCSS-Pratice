## How to setup a Tailwind

step 1: Run the following command

```
npm install -D tailwindcss
npx tailwind init
```

Step 2 : Update tailwind.conf.js file to include this line:
```
content :["*.html"]
```

Step 3 : Create src/input.css to include :
```
@tailwind base;
@tailwind components;
@tailwind utilities;

```

Step 3 : Create src/output.css file to your html:

Step 5 : Run the following command
```
npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch
```
