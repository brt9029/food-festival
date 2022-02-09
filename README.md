# food-festival
- Purpose: Turn an app to a PWA in order to allow users to interact with the website even while there is no internet connection or cell service

## Tools Used
- Google Lighthouse: tool that helps improve performance of web applications by providing audits for performance, accessibility, Progressive Web Apps, and more. It's included in Chrome DevTools
- webpack: simplifies front-end web development by generating static assets from modules with dependencies and using plugins and loaders to help automate certain optimization strategies
- webpack-bundle-analyzer: plugin that allows you to visualize the size of webpack output files with an interactive zoomable treemap
- file-loader: resolves ```import/require()``` on a file into a URL and emits the file into the output directory
- image-webpack-loader: allows you to enhance your image-loading process
- SW-precache-webpack: allows you to use service workers to cache your external project dependencies. Generates a service worker file, using ```sw-precache```, and add it to your build directory
- webpack-PWA-manifest: generates a ```manifest.json``` for your PWA, with auto icon resizing and fingerprinting support
