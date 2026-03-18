# Deprecated / Unmaintained
This project is no longer actively maintained. It may still work, but use it at your own risk.
Please consider forking it if you need continued support.

# gulp-chrome-extention-builder
Make chromium extensions (zip and crx) from gulp.

Usage
-------

```javascript
gulp.task('gcp-zip', function () {
    return gulp.src('./test_ext')
        .pipe(gcp({
            zip: true,
            crx: false
        }))
        .pipe(gulp.dest('./'))
})
```

History
------

v0.1.2 - Only zip supported
