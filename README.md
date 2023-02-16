# HTML-Tailwind-Boilerplate
My go-to template for any website I'm building with a basic HTML markdown and a default(ish) tailwind config file to get me up and running

# THIS IS NOT PRODUCTION READY!

# First launch
1. `npm install -D tailwindcss`
2. `npm install flowbite`
3.  `npm i daisyui`
3.  `tailwindcss init`
4. `npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch`

Once you've launched once, you just need to run 
```
npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch
``` 
next time you're loading up. This is required to gather and build everything.

### Icons
I don't like using SVGs when they can be avoided, so I've built this using fontawesome. I recommend signing up for the free kit here, and then replacing the `https://kit.fontawesome.com/396065dad2.js` url with your new one on line 9 of `src/index.html`.
