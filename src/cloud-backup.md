# Cloud Backup

On this screen you can backup and restore the data and settings used by Cashier. 

The storage is expected to be a WebDAV server.
Cashier will used the configured Server URL as the root folder to use. 

## Setting up a server

The recommended solution is to use RClone. This will be assumed in the description below. You can, however, use any WebDAV server you prefer.
The benefit of using RClone is that you can configure any local or cloud storage 

To run rclone as the WebDAV server, execute:

```
rclone serve webdav <source> --allow-origin "*"
```

where the `<source>` marks any source storage provider supported by RClone. This may be a folder in the local storage or any cloud storage provider. This functionality makes RClone a convenient proxy to a number of cloud storage providers out there.

Using RClone as the storage proxy removes the need for Cashier to handle access credentials to your cloud provider as you can set that up with RClone separately. There is also no need to maintain the APIs for multiple cloud providers.
