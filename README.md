### instructions

```
# install deps, dont run install hooks
# doesnt work with yarn, allow-scripts prefers npm anyway

npm install --ignore-scripts

# run allowed scripts only, as specified in package.json

npx allow-scripts

# see that a non-canonically named dependency ran install hooks

cat attack.txt
```