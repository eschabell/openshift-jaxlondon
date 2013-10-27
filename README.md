JAX London 2013 mobile registration app on OpenShift
====================================================

This is the JAX London 2013 html5/mboile registration app.

Running on OpenShift
--------------------

Create an account at http://openshift.redhat.com/

Create a jbosseap-6.0 application

    rhc app create -t jbosseap-6.0 --from-code git://github.com/eschabell/openshift-jaxlonon.git jaxlondon

That's it, you can now checkout your application at:

    http://jaxlondon-$namespace.rhcloud.com

Don't forget it is better in your mobile browsers!
