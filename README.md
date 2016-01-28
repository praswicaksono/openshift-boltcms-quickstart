Bolt CMS Openshift Quickstart
===

Bolt is a tool for Content Management, which strives to be as simple and straightforward as possible. It is quick to set up, easy to configure, uses elegant templates, and above all: It’s a joy to use. Bolt is created using modern open source libraries, and is best suited to build sites in HTML5 with modern markup.

Running On Openshift
---
Create an account at http://openshift.redhat.com/ and install the client tools (run 'rhc setup' first)

Create a php-5.4 application (you can call your application whatever you want)

    rhc app create bolt php-5.4 mysql-5.5 --from-code=https://github.com/Atriedes/openshift-boltcms-quickstart

That's it, you can now checkout your application at:

    http://bolt-$yournamespace.rhcloud.com

Your BoltCMS now ready to use

Notes
---
You could edit `theme` and `extension` inside openshift directory.
