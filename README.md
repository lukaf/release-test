# Commands

## Create release
```
curl -X POST -H "Authorization: token ${TOKEN}" https://api.github.com/repos/lukaf/release-test/releases -d '{tag_name: bingo, name: This is a release bingo}'
```

