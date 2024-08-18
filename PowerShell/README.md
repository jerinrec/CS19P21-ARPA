## New File
```
New-Item -Path . -ItemType "file" -Name "rec.txt" -Value "This is the content in first file"
```

## New Dir
```
New-Item -Path . -ItemType "directory" -Name "ARPA"
```

## List the contents
```
type rec.txt
```

## Move File
```
Move-Item -Path "<file>" -Destination "ARPA"
```


## UiPath Studio
- Type Argument in `Invoke Powershell`
```
System.IO.*
```
