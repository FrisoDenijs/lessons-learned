# Remove multiple subfolders with same name
`rmdir ./*/bin -r`

# Add prefix to all files in folder
https://stackoverflow.com/a/20874916
`dir | Rename-Item -NewName {"prefix - " + $_.Name}`
