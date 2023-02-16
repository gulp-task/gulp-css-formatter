# gulp-nts-css-formatter

Format CSS style to the old NHN Coding Convention.

## Install

```
$ npm install git+https://oss.navercorp.com/UIT/gulp-nts-css-formatter.git --save-dev
```

## Usage

```javascript
var csssort = require('gulp-nts-css-formatter');

gulp.task('sort', function() {

    return gulp.src(['src/css/*.css'])
            .pipe(csssort())
            .pipe(gulp.dest('src/css'));
});
