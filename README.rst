Alfresco CE - Document & Content Management
===========================================

`Alfresco CE`_ (Community Edition) is the open source alternative 
for Enterprise Content Management. It is the open source version of 
`Alfresco One`_

Alfresco provides modern software built on open standards that unlocks 
the power of business-critical content. With control that IT demands 
and simplicity that end users love, Alfresco's open source technology 
enables global organizations to collaborate more effectively across 
cloud, mobile, hybrid and on-premise environments. Innovating at the 
intersection of content, collaboration and business process, Alfresco 
manages over seven billion documents for more than 1,800 customers in 
195 countries, supporting 11 million users in their daily work. Improve 
business processes, eliminate information silos and experience smarter 
enterprise content management with Alfresco.

This appliance includes all the standard features in `TurnKey Core`_,
and on top of that:

- Alfresco CE configurations:
   
   - installed from upstream WAR to /var/lib/tomcat7/webapps
   - Alfresco CE  base directory set to: /var/local/lib/alfresco

- Tomcat and Java configurations
   
   - Uses OpenJDK 7 Java runtime environment
   - Configured Tomcat admin/manager roles and admin user.
   - Configured Tomcat HTTP connector to bind to port 80 (default:
     8180).
   - Configured SSL port to bind to port 443 (default: 8443).
   - Disabled AJP connector on port 8009 (security).
   - Tomcat and Java environment variables configuration system wide.

- SSL support out of the box.
- Includes postfix MTA (bound to localhost) for sending of email (e.g.
  password recovery).
- Webmin modules for configuring MySQL and Postfix.

Credentials *(passwords set at first boot)*
-------------------------------------------

-  Webmin, SSH, MySQL, phpMyAdmin: username **root**
-  Alfresco CE: username **admin**

.. _Alfresco CE: https://www.alfresco.com/products/community
.. _Alfresco One: https://www.alfresco.com/products/one
.. _TurnKey Core: http://www.turnkeylinux.org/core
