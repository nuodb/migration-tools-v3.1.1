# migration-tools-v3.1.1
The Migrator utility is documented here http://doc.nuodb.com/Latest/Default.htm#NuoDB-Migrator.htm.

In NuoDB v3.2 and v3.3 the Migrator utility may generate additional DDL index create statements that result in failure when creating NuoDB schema objects. The issue will be fixed in a future release. The workaround is to revert to the migrator utility that was released in v3.1.1.

To Install the workaround on Linux: 
1. Download the migrator-3.1.1-linux.tar file
2. Copy the file to your NuoDB home directory (e.g. /opt/nuodb)
3. Unpack the tar file

    tar -xvf migrator-3.1.1-linux.tar
    
