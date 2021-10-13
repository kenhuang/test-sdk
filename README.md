# private-test-sdk

## release
```bash
git checkout main
git fetch --all
git reset --hard origin/main

git tag --delete release
git push --delete origin refs/tags/release

git tag release
git push origin refs/tags/release
```
