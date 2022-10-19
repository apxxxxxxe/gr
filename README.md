# gr
an RSS generator for Gmail

## requirement
- **credentials.json** (A credential JSON file for a Gmail API-enabled application)
  - see the [quickstart document](https://developers.google.com/gmail/api/quickstart/go)

## install
#### 1. install gr
```
go install github.com/apxxxxxxe/gr@latest
```
#### 2. place **credentials.json** at the following directory (lower numbers are read first)
- Windows
1. ```$HOME/gr/```
2. ```$APPDATA/gr/```
3. ```$USERPROFILE/Application Data/gr/```
- other OS
1. ```$HOME/.config/gr/```
## usage
```gr -h```
