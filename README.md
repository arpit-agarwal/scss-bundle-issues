# scss-bundle-issues
- Run `npm install`
- Run `npm start`

This will fail as we ignored inline of `@angular/material/theming` and destination file is `./dist/theme.scss`

However when we don't have ignoredImports it will work fine. Thsi can be validated using
`npm run start:no-ignore`