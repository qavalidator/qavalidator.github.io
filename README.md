# QAvalidator Project Web Site

## Tools

### Work with Jekyll

Use the command `jekyll serve` in the project's directory.
This will serve the result at `http://localhost:4000`,
and update changes immediately (so just press F5 in the browser to see the latest changes).


### Update the Documentation

To publish the latest documentation at https://qavalidator.github.io,
use the Gradle task `copyDocToWebsite` in `qav-doc`. To cleanup beforehand, use `cleanDocInWebsite`.
This updates the AsciiDoc documentation here in the directory `static/doc`.
Just commit and push.
