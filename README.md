# Bug steps

1. [Install Dart Sass](https://sass-lang.com/install) (not the Node.js version!)
   ```
   brew install sass/sass/sass
   ```
1. Install USWDS
   ```
   npm install
   ```
1. Attempt to compile the Sass file:
   ```
   sass test.scss
   ```
1. You'll see an error like:
   ```sh
   Error: Infinity or NaN toInt
   ```
