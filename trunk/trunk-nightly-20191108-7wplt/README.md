# Tests with failure status

## acceptance check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/trunk/trunk-nightly-20191108-7wplt/acceptance/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191108-7wplt/acceptance)
   * [summary.html](https://elek.github.io/ozone-ci-03/trunk/trunk-nightly-20191108-7wplt/acceptance/summary.html)


## integration check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/trunk/trunk-nightly-20191108-7wplt/integration/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191108-7wplt/integration)
   * [summary.md](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191108-7wplt/integration/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191108-7wplt/integration/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.ozone.om.TestOzoneManagerHA](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestOzoneManagerHA.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestOzoneManagerHA-output.txt))
 * [org.apache.hadoop.ozone.om.TestScmSafeMode](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestScmSafeMode.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestScmSafeMode-output.txt))


# Tests with success status

## rat check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/trunk/trunk-nightly-20191108-7wplt/rat/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191108-7wplt/rat)


## checkstyle check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/trunk/trunk-nightly-20191108-7wplt/checkstyle/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191108-7wplt/checkstyle)


## findbugs check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/trunk/trunk-nightly-20191108-7wplt/findbugs/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191108-7wplt/findbugs)
   * [summary.html](https://elek.github.io/ozone-ci-03/trunk/trunk-nightly-20191108-7wplt/findbugs/summary.html)


## checkout check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/trunk/trunk-nightly-20191108-7wplt/checkout/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191108-7wplt/checkout)


## build check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/trunk/trunk-nightly-20191108-7wplt/build/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191108-7wplt/build)


## author check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/trunk/trunk-nightly-20191108-7wplt/author/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191108-7wplt/author)


## unit check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/trunk/trunk-nightly-20191108-7wplt/unit/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191108-7wplt/unit)




# References

 * All the results are saved to [here](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191108-7wplt/)
 * The definition is the build is committed to [here](https://github.com/elek/argo-ozone)
    * The build is defined in [this argo workflow XML](https://github.com/elek/argo-ozone/blob/master/ozone-build.yaml)
    * This report is assembled by the [report script](https://github.com/elek/argo-ozone/blob/master/scripts/report.sh)

This is an experimental build and eventually can be merged to the Apache Hadoop Ozone source tree (after some testing).

In case of any question please contact with elek dot apache dot org.
