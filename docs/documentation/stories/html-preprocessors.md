# HTML Preprocessor integration

Angular CLI supports the [jade/pug](https://pugjs.org) HTML preprocessor.

To use the preprocessor simply add the file to your component's `templateUrl`:

```javascript
@Component({
  selector: 'app-root',
  templateUrl: './app.component.pug',
  styleUrls: ['./app.component.scss']
})
export class AppComponent {
  title = 'app works!';
}
```

Note: The features below are not yet available.

When generating a new project you can also define which extension you want for
style files:

```bash
ng new pug-project --template=pug
```

Or set the default style on an existing project:

```bash
ng set defaults.templateExt pug
```
