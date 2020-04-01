# SQL-Injection-Attacks-and-Defense
SQL Injection Attacks and Defense second edition 2012



So, what exactly is SQL injection? It is the vulnerability that results when you give an
attacker the ability to influence the Structured Query Language (SQL) queries that an
application passes to a back-end database. By being able to influence what is passed to the
database, the attacker can leverage the syntax and capabilities of SQL itself, as well as the
power and flexibility of supporting database functionality and operating system functionality
available to the database. SQL injection is not a vulnerability that exclusively affects Web
applications; any code that accepts input from an untrusted source and then uses that input to
form dynamic SQL statements could be vulnerable (e.g. “fat client” applications in a
client/server architecture). In the past, SQL injection was more typically leveraged against
server side databases, however with the current HTML5 specification, an attacker could
equally execute JavaScript or other codes in order to interact with a client-side database to
steal data. Similarly with mobile applications (such as on the Android platform) malicious
applications and/or client side script can be leveraged in similar ways (see
labs.mwrinfosecurity.com/notices/webcontentresolver/ for more info).




NOTE
--------------------------------------------------------------------------
In the meantime, read through and try out this chapter’s examples again so that you cement your understanding of what SQL injection is and how it happens.
With that knowledge, you’re already a long way toward being able to find, exploit, or fix SQL injection out there in the real world!
---------------------------------------------------------------------------
