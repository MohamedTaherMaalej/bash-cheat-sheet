# Environment Variables Cheat Sheet

## Table of Contents

- [Viewing Environment Variables](#viewing-environment-variables)
- [Setting Environment Variables](#setting-environment-variables)
- [Exporting Variables](#exporting-variables)
- [Unsetting Variables](#unsetting-variables)
- [Special Variables](#special-variables)

## Viewing Environment Variables

### Display All Environment Variables
```bash
printenv
```

### Display Specific Variable
```bash
echo $VAR_NAME
```

## Setting Environment Variables

### Set Temporary Variable (Shell Session Only)
```bash
VAR_NAME=value
```

### Set Permanent Variable (For Current User)
```bash
echo 'export VAR_NAME=value' >> ~/.bashrc
source ~/.bashrc
```

### Set Permanent Variable (For All Users)
```bash
sudo echo 'export VAR_NAME=value' >> /etc/environment
source /etc/environment
```

## Exporting Variables

### Export Variable
```bash
export VAR_NAME=value
```

### Export Variable with Path
```bash
export PATH=$PATH:/new/directory
```

## Unsetting Variables

### Unset Variable
```bash
unset VAR_NAME
```

### Unset All Variables
```bash
env -i bash
```

## Special Variables

### Home Directory
```bash
echo $HOME
```

### Current Working Directory
```bash
echo $PWD
```

### User Name
```bash
echo $USER
```

Feel free to contribute to this cheat sheet by adding more environment variable-related commands or improving existing examples. Follow the [Contributing](../CONTRIBUTING.md) guidelines.
