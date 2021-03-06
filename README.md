# Installing dependencies

```
$ ng add @angular/material
Installing packages for tooling via npm.
Installed packages for tooling via npm.
? Choose a prebuilt theme name, or "custom" for a custom theme: Indigo/Pink        [ Preview: https://material.angular.io?theme=indigo-pink ]
? Set up global Angular Material typography styles? No
? Set up browser animations for Angular Material? Yes
```

```
npm install ng2-charts@2.2.3 --save
```

```
npm install chart.js@2.9.3 --save
```

```
npm install --save-dev ng2-charts-schematics@0.1.7
```

# Add navigation panel

```
ng generate @angular/material:navigation nav
```

# Add dashboard

```
ng generate @angular/material:dashboard dash
```

# Generate charts

```
ng generate ng2-charts-schematics:radar charts/product-sales-chart
ng generate ng2-charts-schematics:pie charts/sales-traffic-chart
ng generate ng2-charts-schematics:line charts/annual-sales-chart 
ng generate ng2-charts-schematics:bar charts/store-sessions-chart
```

# Generate table

```
ng generate @angular/material:table orders-table
```

# links

https://www.smashingmagazine.com/2020/07/responsive-dashboard-angular-material-ng2-charts-schematics   
https://stackoverflow.com/questions/66936633/chart-js-ng2-charts-not-working-on-angular2   
