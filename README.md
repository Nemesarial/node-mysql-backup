## Install

```
npm install -g @cthru/devsql
```

## Use

dbmigration.json
```
{
  host: '192.168.197.128',
  user: 'zhaojun',
  password: 'zhaojun',
  database: 'package_v1',
  tables: ['table1', 'table2'],
  extendedInsert: true,
  addDropTable: true,
  addLocks: true,
  disableKeys: true
}

```

`devsql dbmigration.json`
