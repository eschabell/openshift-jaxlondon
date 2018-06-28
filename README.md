Update: June 2018 moved to [Gitlab](https://gitlab.com/eschabell/openshift-jaxlondon)


JAX London 2013 mobile registration app on OpenShift
====================================================
This is the JAX London 2013 html5 mobile registration app.


Install with one click
----------------------
[![Click to install OpenShift](http://launch-shifter.rhcloud.com/launch/light/Click to install.svg)](https://openshift.redhat.com/app/console/application_type/custom?&cartridges[]=jbosseap-6&initial_git_url=https://github.com/eschabell/openshift-jaxlondon.git&name=jaxlondon)


Manual setup on OpenShift
-------------------------
Create a jbosseap-6.0 application

    rhc app create -t jbosseap-6 --from-code git://github.com/eschabell/openshift-jaxlondon.git jaxlondon

That's it, you can now checkout your application at:

    http://jaxlondon-$namespace.rhcloud.com

Don't forget it is better in your mobile browsers!
