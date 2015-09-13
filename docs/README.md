# DBMS
## Database Meta Data

```
{
  tables: {
    name: 'table_name',
    offset: 'table offset in file',
    records: 'recourds count',
    primary_key: 'primary key column name',
    columns: [
      {
        name: 'column_name',
        type: 'column_type',
        size: 'size(bytes)',
        default: 'default value',
        null: 'boolean'
      }
    ],
    keys: [
      {
        name: 'key_name',
        type: 'key type(unique, index)',
        columns: ['column_name']
      }
    ]
  }
}
```
