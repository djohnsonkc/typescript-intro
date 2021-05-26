Cliff Noted Version of PortExe's Helpful Tutorial

https://www.youtube.com/watch?v=TlYxWnh_mPs

This is the GitHub source
https://github.com/portexe/typescript-the-basics

These are the steps used in creating this sample project that I documented from his very helpful Youtube video.

Create new directory and CD into it
Run npm init (to create package.json - use defaults for everything asked in the CLI)
Run npm install --save-dev typescript (only as a dev dependency)
Enter "code ." (this will open your new folder in VS Code)
Add the "Live Server" addon for VS Code (this allows you to right-click the index.html page and run it in your browser)
Create a dist, src, and public folder
In the public folder, create index.html and styles.css and set up a basic html page with style.css linked
In terminal, run "npx tsc --init" to create the tsconfig.json file
In tsconfig.json, uncomment outDir and rootDir and set outDir to "./dist" and rootDir as "./src"
Create a new script.ts file in the /src directory and just add a console.log('Hello World');
Run "npx tsc" to compile the TypeScript to create JavaScript
To watch changes and automatically update in the browser, use "npx tsc -w" to watch for changes
Now, as you make changes to script.ts, you should see changes reflected in your browser




