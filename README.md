# Angular
Angular Tutorial Series

*node version 20.16.0*
*Angular CLI 19.1.5*

### Setup Commands
## Install Angular CLI
Global Install `npm install -g @angular/cli`
## Check Angular version
`ng version`
## Serve locally on localhost:4200
`ng serve`
## Generate new component
`ng generate component componentName`

### To Utilize Created Components
1. Import component: `import {HomeComponent} from './home/home.component';`
2. Add component to @Component Imports
```
@Component({
  ...
  imports: [HomeComponent],
  ...
})
```
3. Include the components selector inside the parent components @Component template
```
@Component({
  ...
  template: `
    <app-home></app-home>
  `,
  ...
})
```