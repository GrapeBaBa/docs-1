title: Supported Platforms

Supported Platforms
===================

The OSG [release series](../release/release_series.md) are supported on Red Hat Enterprise Linux (RHEL) compatible platforms
for 64-bit Intel architectures according to the following table:

| Platform                   | OSG 3.6 |
|----------------------------|---------|
| CentOS 7                   | &#9989; |
| CentOS Stream 8            | &#9989; |
| Alma Linux 8               | &#9989; |
| Red Hat Enterprise Linux 7 | &#9989; |
| Red Hat Enterprise Linux 8 | &#9989; |
| Rocky Linux 8              | &#9989; |
| Scientifix Linux 7         | &#9989; |

OSG builds and tests its RPMs on the latest releases of the relevant platforms (e.g., in 2021, the RHEL 7 builds were based on RHEL 7.9).
Older platform release versions may not receive thorough testing and may have subtle bugs.
In particular, versions of RHEL/CentOS/SL 7 less than 7.5 have known issues with several pieces of software, including `osg-oasis` and `xrootd-lcmaps`.
In addition, versions of RHEL/CentOS/SL 7 less than 7.8 do not have Python 3, which is required to run HTCondor 9 and HTCondor-CE 5.
If sites run into problems with one of those versions, we will ask them to update to the latest operating system packages as part of the support process.
