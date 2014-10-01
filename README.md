custom_table
============

The example table from views_documentation. Run the next sql query to create to necessary table

CREATE TABLE example_table (
  nid INT(11) NOT NULL         COMMENT 'Primary key; refers to {node}.nid.',
  plain_text_field VARCHAR(32) COMMENT 'Just a plain text field.',
  numeric_field INT(11)        COMMENT 'Just a numeric field.',
  boolean_field INT(1)         COMMENT 'Just an on/off field.',
  timestamp_field INT(8)       COMMENT 'Just a timestamp field.',
  PRIMARY KEY(nid)
);
