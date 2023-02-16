# gulp-css-formatter

Format CSS style to the old Coding Convention.

## Usage

```javascript
var csssort = require('gulp-nts-css-formatter');

gulp.task('sort', function() {

    return gulp.src(['src/css/*.css'])
            .pipe(csssort())
            .pipe(gulp.dest('src/css'));
});
