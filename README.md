`
ng new [ProjectName] --routing
`

`
npm install --save @angular/material @angular/cdk
`

`
npm install --save @angular/animations
`

app.module.ts

`ts
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
`

style.css

`css 
    @angular/material/prebuilt-themes/
`

`
    npm install --save hammerjs
`


main.ts

`
    import 'hammerjs';
`

index.html

`
    <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
`