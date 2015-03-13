These are plugins for jDb, the database abstraction layer of [Jelix](http://jelix.org).

These plugins are deprecated plugins since they use deprecated API of PHP. They are not
bundled with Jelix since Jelix 1.7, and need Jelix 1.7 to work.

Available plugins:

- sqlite (for sqlite 2.0, using deprecated sqlite_* php functions)
- mysql (using deprecated mysql_* php functions)

To install them:

- use Composer (jelix/legacy-db-plugins) or extract them the archive somewhere
- in the mainconfig.ini.php file of your Jelix application, add the path to the legacy-db-plugins
  into the pluginsPath parameter. Example:

```ini
pluginsPath=<some existing path>,app:vendor/jelix/legacy-db-plugins
```

Then you can indicate "sqlite" or "mysql" as 'driver' in the profils.ini.php file.

