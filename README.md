# monitoring-plugins
Simple Nagios-compatible monitoring plugins based on the [Monitoring::Plugin](https://www.monitoring-plugins.org/) Perl module.

We use [OMD](http://omdistro.org/) and had a few monitoring requirements that weren't easily dealt with using the stock plugins or anything we could readily find. These are really developed to solve SAFIRE's requirements, but are made available here in case they're more generically useful to others.

[update-djnro-realms.pl](https://github.com/safire-ac-za/monitoring-plugins/blob/master/update-djnro-realms.pl) isn't a monitoring plugin per-se; it's a tool to generate monitoring config for [DjNRO](http://djnro.grnet.gr/).

