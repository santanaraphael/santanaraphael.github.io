

develop:

bundle exec jekyll serve


deploy:

move _site folder to the github pages repo and commit the changes
cp -a personal_website/_site/. santanaraphael.github.io && rm santanaraphael.github.io/README.md 