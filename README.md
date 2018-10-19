# C5-Err-CollectionSearchIndexAttributes
An exception occurred while executing INSERT INTO CollectionSearchIndexAttributes Field 'ak_language' doesn't have a default value

## Run sql command below in database
ALTER TABLE CollectionSearchIndexAttributes MODIFY ak_language text NULL;
