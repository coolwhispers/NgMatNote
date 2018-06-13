```
    ng new [ProjectName] --routing
    npm install --save @angular/material @angular/cdk
    npm install --save @angular/animations
    npm install --save hammerjs
```

app.module.ts

```ts
@NgModule({
  declarations: [
    AppComponent
  ],
  imports: [
    BrowserModule,
    AppRoutingModule,
    MaterialModule,
  ],
  providers: [],
  bootstrap: [AppComponent]
})
export class AppModule { }
```

style.css

```css
    @import "~@angular/material/prebuilt-themes/indigo-pink.css";
```

main.ts

```ts
    import 'hammerjs';
```

index.html

```html
<link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
```