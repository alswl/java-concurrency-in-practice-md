# JCP


## Fixture

```
find -name "*.txt" -type f -exec  gsed -i -E 's/^([0-9]+\.[0-9]+\.) /## \1 /g' {} \;
find -name "*.txt" -type f -exec  gsed -i -E 's/^([0-9]+\.[0-9]+\.[0-9]+\.) /### \1 /g' {} \;
```
