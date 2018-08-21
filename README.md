# Not good for Git repositories
ln -s /Users/gio/repo/foo.md ./bar/foo.md

# Good for Git repositories
cd ./bar && ln -s ../foo.md foo.md
