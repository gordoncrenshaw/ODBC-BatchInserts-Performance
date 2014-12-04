ODBC-BatchInserts-Performance
=============================

Performance Test for ODBC Batch Inserts

This sample code was created in Visual Studio 2013 Express.  The sample code is written in C.  When creating the Visual Studio project, select a Win32 Console Application, Empty Project.  The compiler will need to be changed to the C compiler.  This can be changed by starting at the main menu and selecting Project -> Preferences -> C/C++ -> All Options -> Compile As -> Compile As C Code (/TC).

The create table statement for this example is for SQL Server.  If the sample is used with another database, the data types in the create table statement will probably need to be changed.  If the create table statement is being modified, the bind parameters will probably need to be changed, too.

ODBCBatchInserts.c is the ANSI version

ODBCBatchInsertsU.c is the UNICODE version
