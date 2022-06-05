# genpasswd2
genpasswd is a cli tool that generates random passwords.

### Usage
```
genpasswd [LENGTH] [-hvdlup]
```

### Options
```
-h --help     Show this screen
-v --verbose  Show password and it's length
-d            Exclude digits from the password
-l            Exclude lowercase letters from the password
-u            Exclude uppercase letters from the password
-p            Exclude punctuation characters from the password
```

### Examples
```
$ genpasswd
Password copied to clipboard.
```
```
$ genpasswd -v
Generated password: vG1y4<lV\82H[1fn
Password length: 16
Password copied to clipboard.
```
```
$ genpasswd 20 -lpv
Generated password: PRH48967U6UMBI567V77
Password length: 20
Password copied to clipboard.
```

## Installation
```
pip install genpasswd2
```
