# andrewcchu-hugo
Source code for personal site.

## Issues/Usage

There exists an issue where the path for CSS and JS for the site (within index.html, see that file's history for more detail) is incorrect. This may my fault, but for now I have made a work around by replacing the generated path string with the correct path string in `deploy.sh`. 

To update the site, put new/updated content within corresponding folders in *this* directory, and then run `bash deploy.sh <COMMIT_MSG>`.

All work will then automatically be done, pushing changes/modifications to the public `andrewcchu.github.io` repository.
