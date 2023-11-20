# Text Processing Cheat Sheet

## Table of Contents

- [Viewing Text](#viewing-text)
- [Manipulating Text](#manipulating-text)
- [Filtering and Searching](#filtering-and-searching)
- [Sorting and Formatting](#sorting-and-formatting)

## Viewing Text

### Display File Content
```bash
cat filename
```

### Display Page-by-Page
```bash
less filename
```
- Press `q` to exit.

### Display Line Numbers
```bash
cat -n filename
```

## Manipulating Text

### Concatenate Files
```bash
cat file1 file2 > merged_file
```

### Cut Columns
```bash
cut -d ',' -f 2 filename.csv
```

### Extract Columns with Awk
```bash
awk -F ',' '{print $2}' filename.csv
```

### Replace Text in File
```bash
sed 's/old_text/new_text/g' filename
```

## Filtering and Searching

### Grep for a Pattern
```bash
grep "pattern" filename
```

### Case-Insensitive Grep
```bash
grep -i "pattern" filename
```

### Invert Match (Exclude Lines)
```bash
grep -v "pattern" filename
```

## Sorting and Formatting

### Sort Lines in File
```bash
sort filename
```

### Sort Numerically
```bash
sort -n filename
```

### Count Unique Lines
```bash
uniq filename
```

### Format JSON
```bash
jq '.' filename.json
```

Feel free to contribute to this cheat sheet by adding more text processing commands or improving existing examples. Follow the [Contributing](../CONTRIBUTING.md) guidelines.
