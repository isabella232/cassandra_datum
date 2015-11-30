# CassandraDatum

## Test setup

Do this in cassandra-cli:

```
use BackupifyMetadata_test; # create it first if it doesn't exist
create column family MockCassandraData with column_type='Super' and comparator='com.backupify.db.DatumType' and subcomparator='UTF8Type';
```

## Copyright

Copyright (c) 2012 Jason Haruska. See LICENSE.txt for further details.
