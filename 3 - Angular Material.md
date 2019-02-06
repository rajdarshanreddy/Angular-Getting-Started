# Angular Material

## Step 1: Install Angular Material, Angular CDK and Angular Animations

```sh
npm install --save @angular/material @angular/cdk @angular/animations
```

## Step 2: Configure animations

Open the file `app.module.ts` and import `BrowserAnimationsModule` module by adding below lines of code in appropriate sections.

```sh
import {BrowserAnimationsModule} from '@angular/platform-browser/animations';

@NgModule({
  ...
  imports: [BrowserAnimationsModule],
  ...
})
export class PizzaPartyAppModule { }
```

## Step 3: Import the component modules

You can import any component fron the list of components that are available at https://material.angular.io/components/categories.

Just to test if Angular Material is working we will import the Button and Checkbox Component.

Open the file `app.module.ts` and import `MatButtonModule` and `MatCheckboxModule` modules by adding below lines of code in appropriate sections.

```sh
import {MatButtonModule, MatCheckboxModule} from '@angular/material';

@NgModule({
  ...
  imports: [MatButtonModule, MatCheckboxModule],
  ...
})
```

## Step 4: Include a theme

Open the file `styles.css` and add the below line. this will include one of Angular Material's prebuilt themes globally in your application
```sh
@import "~@angular/material/prebuilt-themes/indigo-pink.css";
```

## Step 5: Check if Angular Material Works

Open the file `index.html` and add the below lines of code.

```sh
<button mat-raised-button color="primary">Primary</button>
<mat-checkbox class="example-margin" [(ngModel)]="checked">Checked</mat-checkbox>
```
run the application using `ng serve --open`, you should see both the angular material components that we added. 


## References and Resources

Below are links to the documents that you can refer if you have any queries.

* https://material.angular.io/guide/getting-started
* https://material.angular.io/components/categories
