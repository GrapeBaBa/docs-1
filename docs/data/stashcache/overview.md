title: Open Science Data Federation Overview

Open Science Data Federation Overview
========================

The OSG operates the Open Science Data Federation (OSDF), which provides organizations with a method to distribute their data in a scalable manner to thousands of jobs without needing to pre-stage data at each site.

The map below shows the location of the current caches in the federation:

<iframe width="100%" height="500px" frameBorder="0" style="margin-bottom:1em; margin-top:1em" src="https://map.opensciencegrid.org/map/iframe?view=XRootD#38.61687,-97.86621|4|hybrid"></iframe>

## Joining and Using the OSDF

We support three types of deployments:

1. We operate the service for you. All you need is provide us with a Kubernetes host to deploy our container into.
   
    This is our preferred way for you to join.
    It is conceptually described on our [home website](https://osg-htc.org/about/osdf/deploying_an_osdf_origin.html) for an origin.
    A cache would be deployed exactly the same way.

    If this is how you want to join OSDF, please send email to <mailto:support@osg-htc.org> and we will guide you
    through the process.
   
1. You can deploy our container yourself as described in our [documentation](run-stashcache-container.md).
   
1. You can deploy from RPM as described in our [documentation](install-cache.md)

We strongly suggest that you __allow us to operate these services for you (option 1)__. 
The software that implements the service changes frequently enough, and is complicated enough, that keeping up with changes may require significant effort.
If your installation is deemed too out-of-date, your service may be excluded from the OSDF.


__For more information on the OSDF__, please see our [overview page](https://osg-htc.org/about/osdf/).


