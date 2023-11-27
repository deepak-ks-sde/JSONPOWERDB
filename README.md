You can fork it. But before that, please give a star (It's totally free).

http://login2explore.com/jpdb/docs.html

"This project is all about basics of JsonPowerDB (JPDB) and how to use JPDB for CRUD operations."

If you want to make changes in this repo, then create a PR. I will be happy to add more into it. Thanks.!

About JsonPowerDB:

JsonPowerDB is a Real-time, High Performance, Lightweight and Simple to Use, Rest API based Multi-mode
DBMS. JsonPowerDB has ready to use API for Json document DB, RDBMS, Key-value DB, GeoSpatial DB and Time
Series DB functionality. JPDB supports and advocates for true serverless and pluggable API development.

Benefits of using JsonPowerDB:

Simplest way to retrieve data in a JSON format.
Schema-free, Simple to use, Nimble and In-Memory database.
It is built on top of one of the fastest and real-time data indexing engine - PowerIndeX.
It is low level (raw) form of data and is also human readable.
It helps developers in faster coding, in-turn reduces development cost.

Release History:

0.3.2 / 2023-11-03
==================
* Completed the User's Database Replication via pluggable API with the Phase-2 and Phase-3 implementation of replication machanism.
* Added a Javascript client side library "jpdb-rcs-commons.js" to manage the user database replication.
* Added replication management page in Replica Manager Dashboard.
* Added : 'in’, ’!in’, ‘between’ operator for condition in select command - for both indexed and non-indexed columns.
* Added :  functionality for enable / disable of user registration page from Company dashboard settings page.
* Added : functionality for Optimization of RAM from Company Dashboard.
* Added : Improved performance and fixed issue of character-set while uploading CSV / Json data.
* Added NEW serverless pluggable API for stastical analysis functions.
* Improved : INDEX_COLUMN and UNINDEX_COLUMN to allow more than one column in the respective operations.
* Improved : Backend-support for automatic logout in real-time of user from user dashboard, in case if user logout from one tab in a browser or a user gets suspended from company dashboard by admin.
* Improved : Check RAM warnings. Warning check implemented for /api, /kvp, /jpdb at the end of respective api's after methods returning %usage of ram in the response header.
* Improved: Documentation
* Improved: Load the default config properties and save it automatically while plugin the API.
* Fixed: Various small bugs are fixed.
* Fixed : When memory is exhausted is fixed by handling this exception and returning proper response. 
  Work in progress

ScreenShots:

<img width="945" alt="Dashboard" src="https://github.com/deepak-ks-sde/JSONPOWERDB/assets/101627261/55cc05aa-094f-4a3f-b6cc-b21ea932acea">

<img width="959" alt="Server" src="https://github.com/deepak-ks-sde/JSONPOWERDB/assets/101627261/15786993-26c7-45cd-a3ee-65dbe2e5e441">

<img width="959" alt="Server (1)" src="https://github.com/deepak-ks-sde/JSONPOWERDB/assets/101627261/d1b362cd-f040-40b5-a1bf-41c95c3326b5">

![Screenshot (250)](https://github.com/deepak-ks-sde/JSONPOWERDB/assets/101627261/faa408e5-8b10-4f14-81df-fa3ee9368030)
