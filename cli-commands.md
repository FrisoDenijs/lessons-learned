# Remove multiple subfolders with same name
`rmdir ./*/bin -r`

# Add prefix to all files in folder
`dir | Rename-Item -NewName {"prefix - " + $_.Name}`
