Remember to add the url to C:\Windows\System32\drivers\etc\hosts file:

`127.0.0.1 example.com`

# [Error: Unable to Start Debugging on the Web Server](https://docs.microsoft.com/en-us/visualstudio/debugger/error-unable-to-start-debugging-on-the-web-server?view=vs-2017)

## [The remote server returned an error](https://docs.microsoft.com/en-us/visualstudio/debugger/error-unable-to-start-debugging-on-the-web-server?view=vs-2017#server_error)

### (404) Not Found
https://stackoverflow.com/questions/47030437/unable-to-start-debugging-on-the-web-server-the-remote-server-returned-an-error

### (503) Server Unavailable
Check user identification in Application Pool advanced settings, maybe the password needs to be updated.
Restart the application pool.

To change user identification follow the following steps:
1. Go to Application Pools
2. Select the Application Pool concerned and open Advanced Settings
3. Open `Process Model\Identity` 
4. Select the correct built-in identity or add/change the custom identity
