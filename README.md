# angular-heroes
This is our famous angular heroes project, though the default one uses in memory services as backend, instead I have used spring based micro-services deployed in OpenShift.

## Architecture

## Deployment
High level step if you wanted to try:
```
Clone git repository
edit OpenShift gateway URL in hero.service.ts file i.e. **heroesUrl** property
npm install
ng build --prod
copy to tomcat ROOT
```
You all set to test
