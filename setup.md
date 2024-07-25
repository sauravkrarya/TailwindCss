## how to setup tailwind css

step1:   run the following cmd
```
npm install -D tailwindcss  npx tailwindcss init
```

step2:  update the tailwind.config.js file to include this like ,
```
  content: ["*.html"],
```

step3: create src/input.css to include:
```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

step4: link in head the src/output.css file to your  html 

step5: Run the folowing command:
```
npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
```