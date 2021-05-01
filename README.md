# RaceDB-Controller-LogFile
Running init scripts stored in /docker-entrypoint-init.d
RaceDBVersion=v3.0.41-beta-6e8ce7a
/usr/sbin/entrypoint.sh: sourcing bash script: /docker-entrypoint-init.d/01-logstart.sh
databaseEngine="django.db.backends.postgresql"
==========================================
databaseName="racedb"
RACEDB STARTED Sat May  1 18:46:39 UTC 2021
ServerTimeZone="America/Toronto"

python="3.9.4 (default, Apr 10 2021, 15:31:19) 
/usr/sbin/entrypoint.sh: running bash script: /docker-entrypoint-init.d/02-postgres.sh
[GCC 8.3.0]"
Waiting for Postgres to start up...
logFileName="/racedb-data/RaceDB-log.txt"
Checking if the racedb exists...
RaceDBVersion=v3.0.41-beta-6e8ce7a
RaceDB DB already exists. Not creating.
databaseEngine="django.db.backends.postgresql"

databaseName="racedb"
/usr/sbin/entrypoint.sh: sourcing bash script: /docker-entrypoint-init.d/10-configure.sh
ServerTimeZone="America/Toronto"
Configuring RaceDB for psql-local
python="3.9.4 (default, Apr 10 2021, 15:31:19) 
Configured Date/Time for ISO format
[GCC 8.3.0]"

logFileName="/racedb-data/RaceDB-log.txt"
/usr/sbin/entrypoint.sh: sourcing bash script: /docker-entrypoint-init.d/20-data.sh
RaceDBVersion=v3.0.41-beta-6e8ce7a
Database already initialized.
databaseEngine="django.db.backends.postgresql"

databaseName="racedb"
/usr/sbin/entrypoint.sh: sourcing bash script: /docker-entrypoint-init.d/30-backup.sh
ServerTimeZone="America/Toronto"
Backing up database to /racedb-data/backups/racedb-backup-20210501-184640.json
python="3.9.4 (default, Apr 10 2021, 15:31:19) 

[GCC 8.3.0]"
/usr/sbin/entrypoint.sh: sourcing bash script: /docker-entrypoint-init.d/40-import.sh
logFileName="/racedb-data/RaceDB-log.txt"
No SQLITE data to import from /racedb-data/RaceDB.sqlite3
**** Migrating DB...
No JSON data to import from /racedb-data/racedb-import.json
RaceDBVersion=v3.0.41-beta-6e8ce7a

databaseEngine="django.db.backends.postgresql"
/usr/sbin/entrypoint.sh: sourcing bash script: /docker-entrypoint-init.d/95-start.sh
databaseName="racedb"
Starting RaceDB...
ServerTimeZone="America/Toronto"
Operations to perform:
python="3.9.4 (default, Apr 10 2021, 15:31:19) 
  Apply all migrations: admin, auth, contenttypes, core, sessions
[GCC 8.3.0]"
Running pre-migrate handlers for application admin
logFileName="/racedb-data/RaceDB-log.txt"
Running pre-migrate handlers for application auth
**** Switching to Sqlite3 configuration...
Running pre-migrate handlers for application contenttypes
**** Migrating RaceDB.sqlite3...
Running pre-migrate handlers for application sessions
RaceDBVersion=v3.0.41-beta-6e8ce7a
Running pre-migrate handlers for application django_extensions
databaseEngine="django.db.backends.sqlite3"
Running pre-migrate handlers for application core
databaseName="/racedb-data/RaceDB.sqlite3"
Running migrations:
ServerTimeZone="America/Toronto"
  No migrations to apply.
python="3.9.4 (default, Apr 10 2021, 15:31:19) 
  Your models in app(s): 'core' have changes that are not yet reflected in a migration, and so won't be applied.
[GCC 8.3.0]"
  Run 'manage.py makemigrations' to make new migrations, and then re-run 'manage.py migrate' to apply them.
logFileName="/racedb-data/RaceDB-log.txt"
Running post-migrate handlers for application admin
**** Fixing RaceDB.sqlite3 data...
Running post-migrate handlers for application auth
RaceDBVersion=v3.0.41-beta-6e8ce7a
Running post-migrate handlers for application contenttypes
databaseEngine="django.db.backends.sqlite3"
Running post-migrate handlers for application sessions
databaseName="/racedb-data/RaceDB.sqlite3"
Running post-migrate handlers for application django_extensions
ServerTimeZone="America/Toronto"
Running post-migrate handlers for application core
python="3.9.4 (default, Apr 10 2021, 15:31:19) 
Running init scripts stored in /docker-entrypoint-init.d
[GCC 8.3.0]"
/usr/sbin/entrypoint.sh: sourcing bash script: /docker-entrypoint-init.d/01-logstart.sh
logFileName="/racedb-data/RaceDB-log.txt"
==========================================
**** Extracting RaceDB.sqlite3 data to RaceDB.json...
RACEDB STARTED Sat May  1 18:53:22 UTC 2021
RaceDBVersion=v3.0.41-beta-6e8ce7a

databaseEngine="django.db.backends.sqlite3"
/usr/sbin/entrypoint.sh: running bash script: /docker-entrypoint-init.d/02-postgres.sh
databaseName="/racedb-data/RaceDB.sqlite3"
Waiting for Postgres to start up...
ServerTimeZone="America/Toronto"
Checking if the racedb exists...
python="3.9.4 (default, Apr 10 2021, 15:31:19) 
RaceDB DB already exists. Not creating.
[GCC 8.3.0]"

logFileName="/racedb-data/RaceDB-log.txt"
/usr/sbin/entrypoint.sh: sourcing bash script: /docker-entrypoint-init.d/10-configure.sh
**** Cleansing Json File...
Database already configured.
**** Switching to Database configuration...
Configured Date/Time for ISO format
**** Dropping existing database data...

RaceDBVersion=v3.0.41-beta-6e8ce7a
/usr/sbin/entrypoint.sh: sourcing bash script: /docker-entrypoint-init.d/20-data.sh
databaseEngine="django.db.backends.postgresql"
Database already initialized.
databaseName="racedb"

ServerTimeZone="America/Toronto"
/usr/sbin/entrypoint.sh: sourcing bash script: /docker-entrypoint-init.d/30-backup.sh
python="3.9.4 (default, Apr 10 2021, 15:31:19) 
Backing up database to /racedb-data/backups/racedb-backup-20210501-185323.json
[GCC 8.3.0]"

logFileName="/racedb-data/RaceDB-log.txt"
/usr/sbin/entrypoint.sh: sourcing bash script: /docker-entrypoint-init.d/40-import.sh
**** Loading data into database...
Operations to perform:
RaceDBVersion=v3.0.41-beta-6e8ce7a
  Apply all migrations: admin, auth, contenttypes, core, sessions
databaseEngine="django.db.backends.postgresql"
Running migrations:
databaseName="racedb"
  No migrations to apply.
ServerTimeZone="America/Toronto"
  Your models in app(s): 'core' have changes that are not yet reflected in a migration, and so won't be applied.
python="3.9.4 (default, Apr 10 2021, 15:31:19) 
  Run 'manage.py makemigrations' to make new migrations, and then re-run 'manage.py migrate' to apply them.
[GCC 8.3.0]"
Operations to perform:
logFileName="/racedb-data/RaceDB-log.txt"
  Apply all migrations: admin, auth, contenttypes, core, sessions
Traceback (most recent call last):
Running migrations:
  File "/usr/local/lib/python3.9/site-packages/django/db/backends/utils.py", line 84, in _execute
  Applying auth.0012_alter_user_first_name_max_length... OK
    return self.cursor.execute(sql, params)
fix_bad_license_codes and emergency contacts...
psycopg2.errors.StringDataRightTruncation: value too long for type character varying(8)
fix_nation_codes...
fix_non_unique_number_set_entries...
fix_bad_category_hints...
The above exception was the direct cause of the following exception:
fix_phone_numbers...
fix results finish times...
Traceback (most recent call last):
8808 results fixed.
  File "/RaceDB/manage.py", line 38, in <module>
Imported database from /racedb-data/RaceDB.sqlite3 file
    execute_from_command_line(sys.argv)
No JSON data to import from /racedb-data/racedb-import.json
  File "/usr/local/lib/python3.9/site-packages/django/core/management/__init__.py", line 419, in execute_from_command_line

    utility.execute()
/usr/sbin/entrypoint.sh: sourcing bash script: /docker-entrypoint-init.d/95-start.sh
  File "/usr/local/lib/python3.9/site-packages/django/core/management/__init__.py", line 413, in execute
Starting RaceDB...
    self.fetch_command(subcommand).run_from_argv(self.argv)
Operations to perform:
  File "/usr/local/lib/python3.9/site-packages/django/core/management/base.py", line 354, in run_from_argv
  Apply all migrations: admin, auth, contenttypes, core, sessions
    self.execute(*args, **cmd_options)
Running pre-migrate handlers for application admin
  File "/usr/local/lib/python3.9/site-packages/django/core/management/base.py", line 398, in execute
Running pre-migrate handlers for application auth
    output = self.handle(*args, **options)
Running pre-migrate handlers for application contenttypes
  File "/usr/local/lib/python3.9/site-packages/django/core/management/commands/loaddata.py", line 78, in handle
Running pre-migrate handlers for application sessions
    self.loaddata(fixture_labels)
Running pre-migrate handlers for application django_extensions
  File "/usr/local/lib/python3.9/site-packages/django/core/management/commands/loaddata.py", line 123, in loaddata
Running pre-migrate handlers for application core
    self.load_label(fixture_label)
Running migrations:
  File "/usr/local/lib/python3.9/site-packages/django/core/management/commands/loaddata.py", line 190, in load_label
  No migrations to apply.
    obj.save(using=self.using)
  Your models in app(s): 'core' have changes that are not yet reflected in a migration, and so won't be applied.
  File "/usr/local/lib/python3.9/site-packages/django/core/serializers/base.py", line 223, in save
  Run 'manage.py makemigrations' to make new migrations, and then re-run 'manage.py migrate' to apply them.
    models.Model.save_base(self.object, using=using, raw=True, **kwargs)
Running post-migrate handlers for application admin
  File "/usr/local/lib/python3.9/site-packages/django/db/models/base.py", line 763, in save_base
Running post-migrate handlers for application auth
    updated = self._save_table(
Running post-migrate handlers for application contenttypes
  File "/usr/local/lib/python3.9/site-packages/django/db/models/base.py", line 845, in _save_table
Running post-migrate handlers for application sessions
    updated = self._do_update(base_qs, using, pk_val, values, update_fields,
Running post-migrate handlers for application django_extensions
  File "/usr/local/lib/python3.9/site-packages/django/db/models/base.py", line 899, in _do_update
Running post-migrate handlers for application core
    return filtered._update(values) > 0
fix_bad_license_codes and emergency contacts...
  File "/usr/local/lib/python3.9/site-packages/django/db/models/query.py", line 802, in _update
fix_nation_codes...
    return query.get_compiler(self.db).execute_sql(CURSOR)
fix_non_unique_number_set_entries...
  File "/usr/local/lib/python3.9/site-packages/django/db/models/sql/compiler.py", line 1535, in execute_sql
fix_bad_category_hints...
    cursor = super().execute_sql(result_type)
fix_phone_numbers...
  File "/usr/local/lib/python3.9/site-packages/django/db/models/sql/compiler.py", line 1169, in execute_sql
fix results finish times...
    cursor.execute(sql, params)
0 results fixed.
  File "/usr/local/lib/python3.9/site-packages/django/db/backends/utils.py", line 98, in execute
0 Road
    return super().execute(sql, params)
1 Track
  File "/usr/local/lib/python3.9/site-packages/django/db/backends/utils.py", line 66, in execute
2 Cyclocross
    return self._execute_with_wrappers(sql, params, many=False, executor=self._execute)
3 MTB
  File "/usr/local/lib/python3.9/site-packages/django/db/backends/utils.py", line 75, in _execute_with_wrappers
4 BMX
    return executor(sql, params, many, context)
5 Para
  File "/usr/local/lib/python3.9/site-packages/django/db/backends/utils.py", line 84, in _execute
0 Club
    return self.cursor.execute(sql, params)
1 Citizen
  File "/usr/local/lib/python3.9/site-packages/django/db/utils.py", line 90, in __exit__
2 Regional
    raise dj_exc_value.with_traceback(traceback) from exc_value
3 Reg. Champ.
  File "/usr/local/lib/python3.9/site-packages/django/db/backends/utils.py", line 84, in _execute
4 National
    return self.cursor.execute(sql, params)
5 UCI 1.HC
django.db.utils.DataError: Problem installing fixture '/RaceDB/RaceDB.json': Could not load core.ResultMassStart(pk=98546): value too long for type character varying(8)
6 UCI 2.HC
7 UCI 1.1
Cleanup...
8 UCI 2.1
Traceback (most recent call last):
9 UCI 1.2
  File "/RaceDB/./SqliteToDB.py", line 151, in <module>
10 UCI 2.2
    handle_call( ['python', 'manage.py', 'loaddata', JsonFName] )
11 UCI Ncup 1.2
  File "/RaceDB/./SqliteToDB.py", line 112, in handle_call
12 UCI Ncup 2.2
    check_call( args )
13 UCI Wcup
  File "/usr/local/lib/python3.9/subprocess.py", line 373, in check_call
14 UCI 1.Ncup
    raise CalledProcessError(retcode, cmd)
15 UCI 2.Ncup
subprocess.CalledProcessError: Command '['python', 'manage.py', 'loaddata', 'RaceDB.json']' returned non-zero exit status 1.
0 Reference Number Set
RaceDBVersion=v3.0.41-beta-6e8ce7a
Age Age Based
databaseEngine="django.db.backends.postgresql"
     WU13 Women Girls Under 13 <age 10-12>
databaseName="racedb"
     WU15 Women Girls Under 15 <age 13-14>
ServerTimeZone="America/Toronto"
     WU17 Women Girls Under 17 <age 15-16>
python="3.9.4 (default, Apr 10 2021, 15:31:19) 
     WU19 Women Women Under 19 <age 17-18>
[GCC 8.3.0]"
     W_70+ Women Women 70 and over
logFileName="/racedb-data/RaceDB-log.txt"
     WU70 Women Women Under 70 <age 60-69>
     WU60 Women Women Under 60 <age 50-59>
     WU50 Women Women Under 50 <age 40-49>
     WU40 Women Women Under 40 <age 30-39>
     WU30 Women Women Under 30 <age 24-29>
     WU24 Women Women Under 24 <age 19-23>
     MU13 Men Boys Under 13 <age 10-12>
     MU15 Men Boys Under 15 <age 13-14>
     MU17 Men Boys Under 17 <age 15-16>
     MU19 Men Men Under 19 <age 17-18>
     M_70+ Men Men 70 and over
     MU70 Men Men Under 70 <age 60-69>
     MU60 Men Men Under 60 <age 50-59>
     MU50 Men Men Under 50 <age 40-49>
     MU40 Men Men Under 40 <age 30-39>
     MU30 Men Men Under 30 <age 24-29>
     MU24 Men Men Under 24 <age 19-23>
UCI - Road Union Cycliste Internationale Road
     RWU13 Women Road Girls Under 13 <age 10-12>
     RWU15 Women Road Girls Under 15 <age 13-14>
     RWU17 Women Road Girls Under 17 <age 15-16>
     RWJ Women Road Women Junior <age 17-18>
     RWMC Women Road Women Masters <50+>
     RWMB Women Road Women Masters <40-49>
     RWMA Women Road Women Masters <30-39>
     RWE Women Road Women Elite 19+
     RMU13 Men Road Boys Under 13 <age 10-12>
     RMU15 Men Road Boys Under 15 <age 13-14>
     RMU17 Men Road Boys Under 17 <age 15-16>
     RMJ Men Road Men Junior <age 17-18>
     RMMD Men Road Men Masters <60+>
     RMMC Men Road Men Masters <50-59>
     RMMB Men Road Men Masters <40-49>
     RMMA Men Road Men Masters <30-39>
     RMU Men Road Men Under 23
     RME Men Road Men Elite
UCI - MTB Union Cycliste Internationale Mountain Bike
     XWU13.N Women MTB Novice Girls Under 13 <age 10-12>
     XWU13.S Women MTB Senior Girls Under 13 <age 10-12>
     XWU13.E Women MTB Export Girls Under 13 <age 10-12>
     XWU15.N Women MTB Novice Girls Under 15 <age 13-14>
     XWU15.S Women MTB Senior Girls Under 15 <age 13-14>
     XWU15.E Women MTB Expert Girls Under 15 <age 13-14>
     XWU17.N Women MTB Novice Girls Under 17 <age 15-16>
     XWU17.S Women MTB Senior Girls Under 17 <age 15-16>
     XWU17.E Women MTB Expert Girls Under 17 <age 15-16>
     XWJ Women MTB Women Junior <age 17-18>
     XWMC.N Women MTB Novice Women Masters <50+>
     XWMC.S Women MTB Senior Women Masters <50+>
     XWMC.E Women MTB Export Women Masters <50+>
     XWMB.N Women MTB Novice Women Masters <40-49>
     XWMB.S Women MTB Senior Women Masters <40-49>
     XWMB.E Women MTB Export Women Masters <40-49>
     XWMA.N Women MTB Novice Women Masters <30-39>
     XWMA.S Women MTB Senior Women Masters <30-39>
     XWMA.E Women MTB Export Women Masters <30-39>
     XWU Women MTB Women Under 23
     XWE Women MTB Women Elite
     XMU13.N Men MTB Novice Boys Under 13 <age 10-12>
     XMU13.S Men MTB Senior Boys Under 13 <age 10-12>
     XMU13.E Men MTB Export Boys Under 13 <age 10-12>
     XMU15.N Men MTB Novice Boys Under 15 <age 13-14>
     XMU15.S Men MTB Senior Boys Under 15 <age 13-14>
     XMU15.E Men MTB Expert Boys Under 15 <age 13-14>
     XMU17.N Men MTB Novice Boys Under 17 <age 15-16>
     XMU17.S Men MTB Senior Boys Under 17 <age 15-16>
     XMU17.E Men MTB Expert Boys Under 17 <age 15-16>
     XMJ.N Men MTB Novice Men Junior <age 17-18>
     XMJ.S Men MTB Senior Men Junior <age 17-18>
     XMJ.E Men MTB Expert Men Junior <age 17-18>
     XMMD.N Men MTB Novice Men Masters <60+>
     XMMD.S Men MTB Senior Men Masters <60+>
     XMMD.E Men MTB Export Men Masters <60+>
     XMMC.N Men MTB Novice Men Masters <50-59>
     XMMC.S Men MTB Senior Men Masters <50-59>
     XMMC.E Men MTB Export Men Masters <50-59>
     XMMB.N Men MTB Novice Men Masters <40-49>
     XMMB.S Men MTB Senior Men Masters <40-49>
     XMMB.E Men MTB Export Men Masters <40-49>
     XMMA.N Men MTB Novice Men Masters <30-39>
     XMMA.S Men MTB Senior Men Masters <30-39>
     XMMA.E Men MTB Export Men Masters <30-39>
     XMU Men MTB Men Under 23
     XME Men MTB Men Elite
UCI - DH Union Cycliste Internationale Downhill
     DWU13 Women DH Girls Under 13 <age 10-12>
     DWU15 Women DH Girls Under 15 <age 13-14>
     DWU17 Women DH Girls Under 17 <age 15-16>
     DWJ Women DH Women Junior <age 17-18>
     DWE Women DH Women Elite 19+
     DWMC Women DH Women Masters <50+>
     DWMB Women DH Women Masters <40-49>
     DWMA Women DH Women Masters <30-39>
RaceDBVersion=v3.0.41-beta-6e8ce7a
     DMJ Men DH Men Junior <age 17-18>
databaseEngine="django.db.backends.postgresql"
     DME Men DH Men Elite
databaseName="racedb"
     DMU Men DH Men Under 23
ServerTimeZone="America/Toronto"
     DMMD Men DH Men Masters <60+>
python="3.9.4 (default, Apr 10 2021, 15:31:19) 
     DMMC Men DH Men Masters <50-59>
[GCC 8.3.0]"
     DMMB Men DH Men Masters <40-49>
logFileName="/racedb-data/RaceDB-log.txt"
     DMMA Men DH Men Masters <30-39>
**** Migrating DB...
UCI - 4X Union Cycliste Internationale 4-Cross
RaceDBVersion=v3.0.41-beta-6e8ce7a
     4WU13 Women 4X Girls Under 13 <age 10-12>
databaseEngine="django.db.backends.postgresql"
     4WU15 Women 4X Girls Under 15 <age 13-14>
databaseName="racedb"
     4WU17 Women 4X Girls Under 17 <age 15-16>
ServerTimeZone="America/Toronto"
     4WJ Women 4X Women Junior <age 17-18>
python="3.9.4 (default, Apr 10 2021, 15:31:19) 
     4WE Women 4X Women Elite 19+
[GCC 8.3.0]"
     4WMC Women 4X Women Masters <50+>
logFileName="/racedb-data/RaceDB-log.txt"
     4WMB Women 4X Women Masters <40-49>
**** Switching to Sqlite3 configuration...
     4WMA Women 4X Women Masters <30-39>
**** Migrating RaceDB.sqlite3...
     4MJ Men 4X Men Junior <age 17-18>
RaceDBVersion=v3.0.41-beta-6e8ce7a
     4ME Men 4X Men Elite
databaseEngine="django.db.backends.sqlite3"
     4MU Men 4X Men Under 23
databaseName="/racedb-data/RaceDB.sqlite3"
     4MMD Men 4X Men Masters <60+>
ServerTimeZone="America/Toronto"
     4MMC Men 4X Men Masters <50-59>
python="3.9.4 (default, Apr 10 2021, 15:31:19) 
     4MMB Men 4X Men Masters <40-49>
[GCC 8.3.0]"
     4MMA Men 4X Men Masters <30-39>
logFileName="/racedb-data/RaceDB-log.txt"
OCA - Road Ontario Cycling Association
**** Fixing RaceDB.sqlite3 data...
     RWU13 Women Road Girls Under 13 <age 10-12>
RaceDBVersion=v3.0.41-beta-6e8ce7a
     RWU15 Women Road Girls Under 15 <age 13-14>
databaseEngine="django.db.backends.sqlite3"
     RWU17 Women Road Girls Under 17 <age 15-16>
databaseName="/racedb-data/RaceDB.sqlite3"
     RWJ Women Road Women Junior <age 17-18>
ServerTimeZone="America/Toronto"
     RWE.1 Women Road Women Elite 19+
python="3.9.4 (default, Apr 10 2021, 15:31:19) 
     RWE.2 Women Road Women Elite 19+
[GCC 8.3.0]"
     RWMA Women Road Women Masters <30-39>
logFileName="/racedb-data/RaceDB-log.txt"
     RWMB Women Road Women Masters <40-49>
**** Extracting RaceDB.sqlite3 data to RaceDB.json...
     RWMC Women Road Women Masters <50+>
RaceDBVersion=v3.0.41-beta-6e8ce7a
     WSport Women Road Women Sportif
databaseEngine="django.db.backends.sqlite3"
     RMU13 Men Road Boys Under 13 <age 10-12>
databaseName="/racedb-data/RaceDB.sqlite3"
     RMU15 Men Road Boys Under 15 <age 13-14>
ServerTimeZone="America/Toronto"
     RMU17 Men Road Boys Under 17 <age 15-16>
python="3.9.4 (default, Apr 10 2021, 15:31:19) 
     RMJ Men Road Men Junior <age 17-18>
[GCC 8.3.0]"
     RME.4 Men Road Men Elite Ability 4
logFileName="/racedb-data/RaceDB-log.txt"
     RME.3 Men Road Men Elite Ability 3
**** Cleansing Json File...
     RME.2 Men Road Men Elite Ability 2
**** Switching to Database configuration...
     RME.1 Men Road Men Elite Ability 1
**** Dropping existing database data...
     RM.3 Men Road Men Masters Ability 3
RaceDBVersion=v3.0.41-beta-6e8ce7a
     RM.2 Men Road Men Masters Ability 2
databaseEngine="django.db.backends.postgresql"
     RM.1 Men Road Men Masters Ability 1
databaseName="racedb"
     MSport Men Road Men Sportif
ServerTimeZone="America/Toronto"
CC - Road Canadian Cycling
python="3.9.4 (default, Apr 10 2021, 15:31:19) 
     RWU13 Women Road Girls Under 13 <age 10-12>
[GCC 8.3.0]"
     RWU15 Women Road Girls Under 15 <age 13-14>
logFileName="/racedb-data/RaceDB-log.txt"
     RWU17 Women Road Girls Under 17 <age 15-16>
**** Loading data into database...
     RWJ Women Road Women Junior <age 17-18>
RaceDBVersion=v3.0.41-beta-6e8ce7a
     RWE3 Women Road Women Elite 19+ Ability 3
databaseEngine="django.db.backends.postgresql"
     RWE2 Women Road Women Elite 19+ Ability 2
databaseName="racedb"
     RWE1 Women Road Women Elite 19+ Ability 1
ServerTimeZone="America/Toronto"
     RWMC Women Road Women Masters <50+>
python="3.9.4 (default, Apr 10 2021, 15:31:19) 
     RWMB Women Road Women Masters <40-49>
[GCC 8.3.0]"
     RWMA Women Road Women Masters <30-39>
logFileName="/racedb-data/RaceDB-log.txt"
     RMU13 Men Road Boys Under 13 <age 10-12>
Traceback (most recent call last):
     RMU15 Men Road Boys Under 15 <age 13-14>
  File "/usr/local/lib/python3.9/site-packages/django/db/backends/utils.py", line 84, in _execute
     RMU17 Men Road Boys Under 17 <age 15-16>
    return self.cursor.execute(sql, params)
     RMJ Men Road Men Junior <age 17-18>
psycopg2.errors.StringDataRightTruncation: value too long for type character varying(8)
     RME4 Men Road Men Elite Ability 4
     RME3 Men Road Men Elite Ability 3
     RME2 Men Road Men Elite Ability 2
The above exception was the direct cause of the following exception:
     RME1 Men Road Men Elite Ability 1
     RMMD Men Road Men Masters <60+>
Traceback (most recent call last):
     RMMC Men Road Men Masters <50-59>
  File "/RaceDB/manage.py", line 38, in <module>
     RMMB Men Road Men Masters <40-49>
    execute_from_command_line(sys.argv)
     RMMA Men Road Men Masters <30-39>
  File "/usr/local/lib/python3.9/site-packages/django/core/management/__init__.py", line 419, in execute_from_command_line
     RMU Men Road Men Under 23
    utility.execute()
Open Men and Women
  File "/usr/local/lib/python3.9/site-packages/django/core/management/__init__.py", line 413, in execute
     Women Women All Women
    self.fetch_command(subcommand).run_from_argv(self.argv)
     Men Men All Men
  File "/usr/local/lib/python3.9/site-packages/django/core/management/base.py", line 354, in run_from_argv
USAC - Road USA Cycling Road
    self.execute(*args, **cmd_options)
     RWU13 Women Road Girls Under 13 <age 10-12>
  File "/usr/local/lib/python3.9/site-packages/django/core/management/base.py", line 398, in execute
     RWU15 Women Road Girls Under 15 <age 13-14>
    output = self.handle(*args, **options)
     RWU17 Women Road Girls Under 17 <age 15-16>
  File "/usr/local/lib/python3.9/site-packages/django/core/management/commands/loaddata.py", line 78, in handle
     RWJ Women Road Women Junior <age 17-18>
    self.loaddata(fixture_labels)
     RWCat4 Women Road Category 4
  File "/usr/local/lib/python3.9/site-packages/django/core/management/commands/loaddata.py", line 123, in loaddata
     RWCat3 Women Road Category 3
    self.load_label(fixture_label)
     RWCat2 Women Road Category 2
  File "/usr/local/lib/python3.9/site-packages/django/core/management/commands/loaddata.py", line 190, in load_label
     RWCat1 Women Road Category 1
    obj.save(using=self.using)
Running init scripts stored in /docker-entrypoint-init.d
  File "/usr/local/lib/python3.9/site-packages/django/core/serializers/base.py", line 223, in save
/usr/sbin/entrypoint.sh: sourcing bash script: /docker-entrypoint-init.d/01-logstart.sh
    models.Model.save_base(self.object, using=using, raw=True, **kwargs)
==========================================
  File "/usr/local/lib/python3.9/site-packages/django/db/models/base.py", line 763, in save_base
RACEDB STARTED Sat May  1 19:15:19 UTC 2021
    updated = self._save_table(

  File "/usr/local/lib/python3.9/site-packages/django/db/models/base.py", line 845, in _save_table
/usr/sbin/entrypoint.sh: running bash script: /docker-entrypoint-init.d/02-postgres.sh
    updated = self._do_update(base_qs, using, pk_val, values, update_fields,
Waiting for Postgres to start up...
  File "/usr/local/lib/python3.9/site-packages/django/db/models/base.py", line 899, in _do_update
Checking if the racedb exists...
    return filtered._update(values) > 0
RaceDB DB already exists. Not creating.
  File "/usr/local/lib/python3.9/site-packages/django/db/models/query.py", line 802, in _update

    return query.get_compiler(self.db).execute_sql(CURSOR)
/usr/sbin/entrypoint.sh: sourcing bash script: /docker-entrypoint-init.d/10-configure.sh
  File "/usr/local/lib/python3.9/site-packages/django/db/models/sql/compiler.py", line 1535, in execute_sql
Database already configured.
    cursor = super().execute_sql(result_type)
Configured Date/Time for ISO format
  File "/usr/local/lib/python3.9/site-packages/django/db/models/sql/compiler.py", line 1169, in execute_sql

    cursor.execute(sql, params)
/usr/sbin/entrypoint.sh: sourcing bash script: /docker-entrypoint-init.d/20-data.sh
  File "/usr/local/lib/python3.9/site-packages/django/db/backends/utils.py", line 98, in execute
Database already initialized.
    return super().execute(sql, params)

  File "/usr/local/lib/python3.9/site-packages/django/db/backends/utils.py", line 66, in execute
/usr/sbin/entrypoint.sh: sourcing bash script: /docker-entrypoint-init.d/30-backup.sh
    return self._execute_with_wrappers(sql, params, many=False, executor=self._execute)
Backing up database to /racedb-data/backups/racedb-backup-20210501-191519.json
  File "/usr/local/lib/python3.9/site-packages/django/db/backends/utils.py", line 75, in _execute_with_wrappers

    return executor(sql, params, many, context)
/usr/sbin/entrypoint.sh: sourcing bash script: /docker-entrypoint-init.d/40-import.sh
  File "/usr/local/lib/python3.9/site-packages/django/db/backends/utils.py", line 84, in _execute
Operations to perform:
    return self.cursor.execute(sql, params)
  Apply all migrations: admin, auth, contenttypes, core, sessions
  File "/usr/local/lib/python3.9/site-packages/django/db/utils.py", line 90, in __exit__
Running migrations:
    raise dj_exc_value.with_traceback(traceback) from exc_value
  No migrations to apply.
  File "/usr/local/lib/python3.9/site-packages/django/db/backends/utils.py", line 84, in _execute
  Your models in app(s): 'core' have changes that are not yet reflected in a migration, and so won't be applied.
    return self.cursor.execute(sql, params)
  Run 'manage.py makemigrations' to make new migrations, and then re-run 'manage.py migrate' to apply them.
django.db.utils.DataError: Problem installing fixture '/RaceDB/RaceDB.json': Could not load core.ResultMassStart(pk=98546): value too long for type character varying(8)
Operations to perform:
  Apply all migrations: admin, auth, contenttypes, core, sessions
Cleanup...
Running migrations:
Traceback (most recent call last):
  Applying auth.0012_alter_user_first_name_max_length... OK
  File "/RaceDB/./SqliteToDB.py", line 151, in <module>
fix_bad_license_codes and emergency contacts...
    handle_call( ['python', 'manage.py', 'loaddata', JsonFName] )
fix_nation_codes...
  File "/RaceDB/./SqliteToDB.py", line 112, in handle_call
fix_non_unique_number_set_entries...
    check_call( args )
fix_bad_category_hints...
  File "/usr/local/lib/python3.9/subprocess.py", line 373, in check_call
fix_phone_numbers...
    raise CalledProcessError(retcode, cmd)
fix results finish times...
subprocess.CalledProcessError: Command '['python', 'manage.py', 'loaddata', 'RaceDB.json']' returned non-zero exit status 1.
8808 results fixed.
RaceDBVersion=v3.0.41-beta-6e8ce7a
Imported database from /racedb-data/RaceDB.sqlite3 file
databaseEngine="django.db.backends.postgresql"
No JSON data to import from /racedb-data/racedb-import.json
databaseName="racedb"

ServerTimeZone="America/Toronto"
/usr/sbin/entrypoint.sh: sourcing bash script: /docker-entrypoint-init.d/95-start.sh
python="3.9.4 (default, Apr 10 2021, 15:31:19) 
Starting RaceDB...
[GCC 8.3.0]"
Operations to perform:
logFileName="/racedb-data/RaceDB-log.txt"
  Apply all migrations: admin, auth, contenttypes, core, sessions
Running pre-migrate handlers for application admin
Running pre-migrate handlers for application auth
Running pre-migrate handlers for application contenttypes
Running pre-migrate handlers for application sessions
Running pre-migrate handlers for application django_extensions
Running pre-migrate handlers for application core
Running migrations:
  No migrations to apply.
  Your models in app(s): 'core' have changes that are not yet reflected in a migration, and so won't be applied.
  Run 'manage.py makemigrations' to make new migrations, and then re-run 'manage.py migrate' to apply them.
Running post-migrate handlers for application admin
Running post-migrate handlers for application auth
Running post-migrate handlers for application contenttypes
Running post-migrate handlers for application sessions
Running post-migrate handlers for application django_extensions
Running post-migrate handlers for application core
fix_bad_license_codes and emergency contacts...
fix_nation_codes...
fix_non_unique_number_set_entries...
fix_bad_category_hints...
fix_phone_numbers...
fix results finish times...
0 results fixed.
0 Road
1 Track
2 Cyclocross
3 MTB
4 BMX
5 Para
0 Club
1 Citizen
2 Regional
3 Reg. Champ.
4 National
5 UCI 1.HC
6 UCI 2.HC
7 UCI 1.1
8 UCI 2.1
9 UCI 1.2
10 UCI 2.2
11 UCI Ncup 1.2
12 UCI Ncup 2.2
13 UCI Wcup
14 UCI 1.Ncup
15 UCI 2.Ncup
0 Reference Number Set
Age Age Based
     WU13 Women Girls Under 13 <age 10-12>
     WU15 Women Girls Under 15 <age 13-14>
     WU17 Women Girls Under 17 <age 15-16>
     WU19 Women Women Under 19 <age 17-18>
     W_70+ Women Women 70 and over
     WU70 Women Women Under 70 <age 60-69>
     WU60 Women Women Under 60 <age 50-59>
     WU50 Women Women Under 50 <age 40-49>
     WU40 Women Women Under 40 <age 30-39>
     WU30 Women Women Under 30 <age 24-29>
     WU24 Women Women Under 24 <age 19-23>
     MU13 Men Boys Under 13 <age 10-12>
     MU15 Men Boys Under 15 <age 13-14>
     MU17 Men Boys Under 17 <age 15-16>
     MU19 Men Men Under 19 <age 17-18>
     M_70+ Men Men 70 and over
     MU70 Men Men Under 70 <age 60-69>
     MU60 Men Men Under 60 <age 50-59>
     MU50 Men Men Under 50 <age 40-49>
     MU40 Men Men Under 40 <age 30-39>
     MU30 Men Men Under 30 <age 24-29>
     MU24 Men Men Under 24 <age 19-23>
UCI - Road Union Cycliste Internationale Road
     RWU13 Women Road Girls Under 13 <age 10-12>
     RWU15 Women Road Girls Under 15 <age 13-14>
     RWU17 Women Road Girls Under 17 <age 15-16>
     RWJ Women Road Women Junior <age 17-18>
     RWMC Women Road Women Masters <50+>
     RWMB Women Road Women Masters <40-49>
     RWMA Women Road Women Masters <30-39>
     RWE Women Road Women Elite 19+
     RMU13 Men Road Boys Under 13 <age 10-12>
     RMU15 Men Road Boys Under 15 <age 13-14>
     RMU17 Men Road Boys Under 17 <age 15-16>
     RMJ Men Road Men Junior <age 17-18>
     RMMD Men Road Men Masters <60+>
     RMMC Men Road Men Masters <50-59>
     RMMB Men Road Men Masters <40-49>
     RMMA Men Road Men Masters <30-39>
     RMU Men Road Men Under 23
     RME Men Road Men Elite
UCI - MTB Union Cycliste Internationale Mountain Bike
     XWU13.N Women MTB Novice Girls Under 13 <age 10-12>
     XWU13.S Women MTB Senior Girls Under 13 <age 10-12>
     XWU13.E Women MTB Export Girls Under 13 <age 10-12>
     XWU15.N Women MTB Novice Girls Under 15 <age 13-14>
     XWU15.S Women MTB Senior Girls Under 15 <age 13-14>
     XWU15.E Women MTB Expert Girls Under 15 <age 13-14>
     XWU17.N Women MTB Novice Girls Under 17 <age 15-16>
     XWU17.S Women MTB Senior Girls Under 17 <age 15-16>
     XWU17.E Women MTB Expert Girls Under 17 <age 15-16>
     XWJ Women MTB Women Junior <age 17-18>
     XWMC.N Women MTB Novice Women Masters <50+>
     XWMC.S Women MTB Senior Women Masters <50+>
     XWMC.E Women MTB Export Women Masters <50+>
     XWMB.N Women MTB Novice Women Masters <40-49>
     XWMB.S Women MTB Senior Women Masters <40-49>
     XWMB.E Women MTB Export Women Masters <40-49>
     XWMA.N Women MTB Novice Women Masters <30-39>
     XWMA.S Women MTB Senior Women Masters <30-39>
     XWMA.E Women MTB Export Women Masters <30-39>
     XWU Women MTB Women Under 23
     XWE Women MTB Women Elite
     XMU13.N Men MTB Novice Boys Under 13 <age 10-12>
     XMU13.S Men MTB Senior Boys Under 13 <age 10-12>
     XMU13.E Men MTB Export Boys Under 13 <age 10-12>
     XMU15.N Men MTB Novice Boys Under 15 <age 13-14>
     XMU15.S Men MTB Senior Boys Under 15 <age 13-14>
     XMU15.E Men MTB Expert Boys Under 15 <age 13-14>
     XMU17.N Men MTB Novice Boys Under 17 <age 15-16>
     XMU17.S Men MTB Senior Boys Under 17 <age 15-16>
     XMU17.E Men MTB Expert Boys Under 17 <age 15-16>
     XMJ.N Men MTB Novice Men Junior <age 17-18>
     XMJ.S Men MTB Senior Men Junior <age 17-18>
     XMJ.E Men MTB Expert Men Junior <age 17-18>
     XMMD.N Men MTB Novice Men Masters <60+>
     XMMD.S Men MTB Senior Men Masters <60+>
     XMMD.E Men MTB Export Men Masters <60+>
     XMMC.N Men MTB Novice Men Masters <50-59>
     XMMC.S Men MTB Senior Men Masters <50-59>
     XMMC.E Men MTB Export Men Masters <50-59>
     XMMB.N Men MTB Novice Men Masters <40-49>
     XMMB.S Men MTB Senior Men Masters <40-49>
     XMMB.E Men MTB Export Men Masters <40-49>
     XMMA.N Men MTB Novice Men Masters <30-39>
     XMMA.S Men MTB Senior Men Masters <30-39>
     XMMA.E Men MTB Export Men Masters <30-39>
     XMU Men MTB Men Under 23
     XME Men MTB Men Elite
UCI - DH Union Cycliste Internationale Downhill
     DWU13 Women DH Girls Under 13 <age 10-12>
     DWU15 Women DH Girls Under 15 <age 13-14>
     DWU17 Women DH Girls Under 17 <age 15-16>
     DWJ Women DH Women Junior <age 17-18>
     DWE Women DH Women Elite 19+
     DWMC Women DH Women Masters <50+>
     DWMB Women DH Women Masters <40-49>
     DWMA Women DH Women Masters <30-39>
     DMJ Men DH Men Junior <age 17-18>
     DME Men DH Men Elite
     DMU Men DH Men Under 23
     DMMD Men DH Men Masters <60+>
     DMMC Men DH Men Masters <50-59>
     DMMB Men DH Men Masters <40-49>
     DMMA Men DH Men Masters <30-39>
UCI - 4X Union Cycliste Internationale 4-Cross
     4WU13 Women 4X Girls Under 13 <age 10-12>
     4WU15 Women 4X Girls Under 15 <age 13-14>
     4WU17 Women 4X Girls Under 17 <age 15-16>
     4WJ Women 4X Women Junior <age 17-18>
     4WE Women 4X Women Elite 19+
     4WMC Women 4X Women Masters <50+>
     4WMB Women 4X Women Masters <40-49>
     4WMA Women 4X Women Masters <30-39>
     4MJ Men 4X Men Junior <age 17-18>
     4ME Men 4X Men Elite
     4MU Men 4X Men Under 23
     4MMD Men 4X Men Masters <60+>
     4MMC Men 4X Men Masters <50-59>
     4MMB Men 4X Men Masters <40-49>
     4MMA Men 4X Men Masters <30-39>
OCA - Road Ontario Cycling Association
     RWU13 Women Road Girls Under 13 <age 10-12>
     RWU15 Women Road Girls Under 15 <age 13-14>
     RWU17 Women Road Girls Under 17 <age 15-16>
     RWJ Women Road Women Junior <age 17-18>
     RWE.1 Women Road Women Elite 19+
     RWE.2 Women Road Women Elite 19+
     RWMA Women Road Women Masters <30-39>
     RWMB Women Road Women Masters <40-49>
     RWMC Women Road Women Masters <50+>
     WSport Women Road Women Sportif
     RMU13 Men Road Boys Under 13 <age 10-12>
     RMU15 Men Road Boys Under 15 <age 13-14>
     RMU17 Men Road Boys Under 17 <age 15-16>
     RMJ Men Road Men Junior <age 17-18>
     RME.4 Men Road Men Elite Ability 4
     RME.3 Men Road Men Elite Ability 3
     RME.2 Men Road Men Elite Ability 2
     RME.1 Men Road Men Elite Ability 1
     RM.3 Men Road Men Masters Ability 3
     RM.2 Men Road Men Masters Ability 2
     RM.1 Men Road Men Masters Ability 1
     MSport Men Road Men Sportif
CC - Road Canadian Cycling
     RWU13 Women Road Girls Under 13 <age 10-12>
     RWU15 Women Road Girls Under 15 <age 13-14>
     RWU17 Women Road Girls Under 17 <age 15-16>
     RWJ Women Road Women Junior <age 17-18>
     RWE3 Women Road Women Elite 19+ Ability 3
     RWE2 Women Road Women Elite 19+ Ability 2
     RWE1 Women Road Women Elite 19+ Ability 1
     RWMC Women Road Women Masters <50+>
     RWMB Women Road Women Masters <40-49>
     RWMA Women Road Women Masters <30-39>
     RMU13 Men Road Boys Under 13 <age 10-12>
     RMU15 Men Road Boys Under 15 <age 13-14>
     RMU17 Men Road Boys Under 17 <age 15-16>
     RMJ Men Road Men Junior <age 17-18>
     RME4 Men Road Men Elite Ability 4
     RME3 Men Road Men Elite Ability 3
     RME2 Men Road Men Elite Ability 2
     RME1 Men Road Men Elite Ability 1
     RMMD Men Road Men Masters <60+>
     RMMC Men Road Men Masters <50-59>
     RMMB Men Road Men Masters <40-49>
     RMMA Men Road Men Masters <30-39>
     RMU Men Road Men Under 23
Open Men and Women
     Women Women All Women
     Men Men All Men
USAC - Road USA Cycling Road
     RWU13 Women Road Girls Under 13 <age 10-12>
     RWU15 Women Road Girls Under 15 <age 13-14>
     RWU17 Women Road Girls Under 17 <age 15-16>
     RWJ Women Road Women Junior <age 17-18>
     RWCat4 Women Road Category 4
     RWCat3 Women Road Category 3
     RWCat2 Women Road Category 2
     RWCat1 Women Road Category 1

