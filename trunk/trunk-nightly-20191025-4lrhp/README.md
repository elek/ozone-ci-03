# Tests with failure status

## integration check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/trunk/trunk-nightly-20191025-4lrhp/integration/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191025-4lrhp/integration)
   * [summary.md](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191025-4lrhp/integration/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191025-4lrhp/integration/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.ozone.om.TestOzoneManagerHA](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestOzoneManagerHA.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestOzoneManagerHA-output.txt))
 * [org.apache.hadoop.ozone.om.TestScmSafeMode](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestScmSafeMode.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestScmSafeMode-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestDeleteWithSlowFollower](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestDeleteWithSlowFollower.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestDeleteWithSlowFollower-output.txt))


# Tests with success status

## checkstyle check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/trunk/trunk-nightly-20191025-4lrhp/checkstyle/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191025-4lrhp/checkstyle)


## findbugs check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/trunk/trunk-nightly-20191025-4lrhp/findbugs/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191025-4lrhp/findbugs)
   * [summary.html](https://elek.github.io/ozone-ci-03/trunk/trunk-nightly-20191025-4lrhp/findbugs/summary.html)


## acceptance check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/trunk/trunk-nightly-20191025-4lrhp/acceptance/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191025-4lrhp/acceptance)
   * [summary.html](https://elek.github.io/ozone-ci-03/trunk/trunk-nightly-20191025-4lrhp/acceptance/summary.html)


## checkout check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/trunk/trunk-nightly-20191025-4lrhp/checkout/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191025-4lrhp/checkout)


## author check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/trunk/trunk-nightly-20191025-4lrhp/author/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191025-4lrhp/author)


## build check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/trunk/trunk-nightly-20191025-4lrhp/build/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191025-4lrhp/build)


## rat check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/trunk/trunk-nightly-20191025-4lrhp/rat/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191025-4lrhp/rat)


## unit check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/trunk/trunk-nightly-20191025-4lrhp/unit/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191025-4lrhp/unit)




# References

 * All the results are saved to [here](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191025-4lrhp/)
 * The definition is the build is committed to [here](https://github.com/elek/argo-ozone)
    * The build is defined in [this argo workflow XML](https://github.com/elek/argo-ozone/blob/master/ozone-build.yaml)
    * This report is assembled by the [report script](https://github.com/elek/argo-ozone/blob/master/scripts/report.sh)

This is an experimental build and eventually can be merged to the Apache Hadoop Ozone source tree (after some testing).

In case of any question please contact with elek dot apache dot org.
