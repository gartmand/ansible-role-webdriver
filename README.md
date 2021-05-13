# ansible-role-webdriver

This role allows for Ansible to install multiple WebDrivers (Chrome, Firefox, etc.) to the server.
This can be helpful because multiple teams (or even one team) working on one CI server may need access to multiple drivers,
or even multiple versions of the same driver. Relying in a single ChromeDriver version, for example,
might get cumbersome if another team wants another version of ChromeDriver for their own Selenium tests.

This role has been tested with ansible version(s):
* 2.4.3.0
