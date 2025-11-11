# Remove multiple subfolders with same name
`rmdir ./*/bin -r`

# Add prefix to all files in folder
https://stackoverflow.com/a/20874916

`dir | Rename-Item -NewName {"prefix - " + $_.Name}`

# Allow scripts to run in powershell
https://dev.to/jackfd120/resolving-npm-execution-policy-error-in-powershell-a-step-by-step-guide-for-developers-32ip

`Set-ExecutionPolicy RemoteSigned`
