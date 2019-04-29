**Count the number of lines for a git repository**

`git ls-files | xargs wc -l`

**Count with .js file extensions**

`git ls-files | grep -E \*.js$ | xargs wc -l`
