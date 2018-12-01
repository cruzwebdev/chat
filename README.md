# Chat

#### Chat, Nov. 28, 2018

#### By _**Conor McCarthy**_

## Description

This is a chatroom and direct message application. The application is built with Angular 6, Firebase and deployed on AWS. A user can create their own chatroom, go to a previously created chat room or directly message another user. My code is broken up down by pages which hold their components. 

View the deployed application here: http://cloud.connorangularchat.com.s3-website.us-west-2.amazonaws.com

## Setup/Installation Requirements

- Open file in your terminal
- Clone the repository
- Navigate to the file in your terminal and enter $ NPM Install
- Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.
- Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.
- Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.
-include an evironments.ts file with the following code and insert your own Firebase project details:
`export const environment = { production: false, firebase: { apiKey: '', authDomain: '', databaseURL: '', projectId: '', storageBucket: '', messagingSenderId: '' } };`

## Known Bugs

_None._

## Under Construction
The profile section is currently under construction. A user can upload a profile picture, but the bio does not update. I am adding functionality to send images in the chat section. I am working on optimizing the site for mobile.

## Support and contact details

- connormaccarthy8@gmail.com\_
- To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

## Technologies Used

- JavaScript
- NPM
- Karma
- Jasmine
- GitHub
- Angular
- Bootstrap
- Firebase
- Amazon AWS

### License

Copyright (c) 2018 **_Connor McCarthy_**
