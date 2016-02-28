# RedisCacheSampleExport

## Filling in strings from Portal.azure.com
- From Cache blade
	- subscriptionId
	- resourceGroup
	- cacheName

- From storage blade
	- storageAccountConnectionString = Settings -> Access keys -> Connection strings
	
- Bearer
	1. Open developer console on browser (F12)
	2. Select one of the invoke calls and view headers
	3. Copy the text after "Bearer "

![Console image](https://github.com/JimRoberts-MS/RedisCacheSampleExport/blob/master/bearer.png)
	
## As desired
- containerToWriteTo
- blobPrefix