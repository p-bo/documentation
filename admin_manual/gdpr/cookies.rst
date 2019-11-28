=======
Cookies
=======

.. sectionauthor:: Björn Schießle <bjoern@nextcloud.com>
.. _cookies:

Nextcloud only stores cookies needed for Nextcloud to work properly. All cookies comes from your Nextcloud server directly, no 3rd-party cookies will be send to your system. Regarding GDPR, `only data which contain personal data are relevant`_.

.. _`only data which contain personal data are relevant`: https://gdpr-info.eu/recitals/no-26/


Cookies stored by Nextcloud
===========================

====================  ====================================  ================
 Cookie                  Data Stored                             Lifetime
====================  ====================================  ================
 Session cookie        - session ID                          24 minutes
                       - user ID
                       - secret token (used to decrypt 
                         the session on the server)
 Same-site cookie      no user-related data are stored,      forever
                       all same-site cookies are the same
                       for all users on all Nextcloud 
                       instances
 Remember-me cookie    - user id                             15 days (can be
                       - secret token                        (configured)
====================  ====================================  ================

