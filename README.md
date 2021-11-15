## SIREMIS

### Web Management Interface for Kamailio SIP Server

v5.3.0

Web: https://www.siremis.org

Compatible with Kamailio: v5.2.x and v5.3.x

  * https://www.kamailio.org

### Install

Visit next links for references and guidelines on how to install Siremis:

  * https://kb.asipto.com/siremis:index
  * https://www.siremis.org/install/

To install and deploy Siremis using Docker, see:

  * misc/docker/README.md
  * on github: https://github.com/asipto/siremis/tree/master/misc/docker

### Security Considerations

Siremis is an administration tool, not audited for security, intended to run on a protected environment.

It is recommended to:

  * run it in a private network
  * run it over HTTPS
  * add extra protection at HTTP server or firewall layers (e.g., HTTP auth, IP restrictions, etc)

### Resources

Mailing lists

  * use Kamailio mailing lists to ask questions about SIREMIS
    * Kamailio Users Mailing List: <sr-users@lists.kamailio.org>
    * Kamailio Devel Mailing List: <sr-dev@lists.kamailio.org>

IRC Channel:

  * #kamailio on irc.freenode.net

Github Project:

  * https://github.com/asipto/siremis

Paid support or development extensions for SIREMIS:

  * Asipto - https://www.asipto.com

Project Management:

  * Daniel-Constantin Mierla
  * Elena-Ramona Modroiu

### Licensing

  * code and modules developed by ASIPTO are released under GPLv2 license, or (at your option) any later version

Details about licenses of the external components distributed within Siremis project:

  * PHPOpenBiz and Cubi frameworks included in SIREMIS tarball are licensed under BSD Style-License (https://github.com/phpOpenbiz/openbiz-cubi)
  * OFC2 library used to build charts in old versions (SIREMIS less than v5.0.0) is licensed under LGPL (http://teethgrinder.co.uk/open-flash-chart-2/)
  * echarts library used to build charts in new versions (SIREMIS v5.0.0 or greater) is licensed under BSD-3-Clause (https://github.com/ecomfe/echarts)
  * smarty (v2.6.x) php templates library is licensed under LGPL (https://github.com/smarty-php/smarty/)
