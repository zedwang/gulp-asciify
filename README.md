# gulp-asciify
A gulp component
require <code>asciify</code>
#Install
```
$ npm install gulp-asciify --save-dev
```
#Demo
```
gulp.task('asciify',() => {
    return gulp.src('dist/index.html')
        .pipe(require('gulp-asciify')('./app/ascii/ascii.txt'))
        .pipe(gulp.dest('dist/'))
})

```
