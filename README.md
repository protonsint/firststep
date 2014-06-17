First Step on OpenShift
================
This is a very simple example of how to deploy a servlet to JBoss Application Server 7 on OpenShift

Create an account at http://openshift.redhat.com/

Install the client tools: https://www.openshift.com/developers/rhc-client-tools-install

Create a JBoss EAP application based on this repo's code (you can call your application whatever you want, here we've called it firststep)

    rhc app create firststep jbossas-7 --from-code=https://github.com/rkmallik/firststep

That's it, you can now checkout your application at:

http://firststep-$yournamespace.rhcloud.com/HelloWorld
