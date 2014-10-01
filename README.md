custom_table
============

The example table from views_documentation. Run the next sql query to create to necessary table
```sql
CREATE TABLE custom_table (
  nid INT(11) NOT NULL         /*'Primary key; refers to {node}.nid.'*/,
  plain_text_field VARCHAR(32) /* 'Just a plain text field.'*/,
  numeric_field INT(11)        /* 'Just a numeric field.'*/,
  boolean_field INT(1)         /* 'Just an on/off field.'*/,
  timestamp_field INT(8)       /*'Just a timestamp field.'*/,
  PRIMARY KEY(nid)
);
```
