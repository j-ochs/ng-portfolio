# NgPortfolio

Serves as a living resume to highlight my Computer Science experience.
This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.2.1.


## Development server

Run `ng serve` or `npm start` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.


## Github Pages Publishing

To publish the site, first commit all changes to the master (or other) branch.
Then run `ng build --env=prod --base-href "https://j-ochs.github.io/ng-portfolio/"` to generate dist folder with proper base link. 

Finally, run `ngh` to publish to Github Pages at the above link (*this command will auto-commit to the __gh-pages__ branch*). 
To include a commit message, instead run `ngh --message="your message message`


## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.


## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
