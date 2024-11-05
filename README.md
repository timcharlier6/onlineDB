# onlineDB

Replit for my online ressources database.

## To change the name
sqlite3 online.db .dump > dump.sql
sqlite3 main.db < dump.sql

## To copy paste into repl
ctrl shift v

## List tables
.tables 

or

SELECT name FROM sqlite_master WHERE type='table' ORDER BY name;

## List table structure
.schema mytable 

