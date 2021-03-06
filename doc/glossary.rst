Glossary
========

.. glossary::
   :sorted:

   ownCloud Client
   oCC
     Name of the official ownCloud syncing client for desktop, which runs on
     Windows, Mac OS X and Linux. It is based Mirall, and uses the CSync
     sync engine for synchronization with the ownCloud server.

   ownCloud Server
     The server counter part of ownCloud Client as provided by the ownCloud
     community.

   mtime
   modification time
   file modification time
     File property used to determine whether the servers' or the clients' file
     is more recent. Standard procedure in oCC 1.0.5 and earlier, used by
     oCC 1.1 and later only when no sync database exists and files already
     exist in the client directory.

   unique id
     ID assigned to every file starting with ownCloud server 4.5 and submitted
     via the HTTP ``Etag``. Used to check if files on client and server have
     changed.
