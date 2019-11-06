# Tests with failure status

## acceptance check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/trunk/trunk-nightly-20191106-sqq5g/acceptance/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191106-sqq5g/acceptance)
   * [summary.html](https://elek.github.io/ozone-ci-03/trunk/trunk-nightly-20191106-sqq5g/acceptance/summary.html)


## integration check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/trunk/trunk-nightly-20191106-sqq5g/integration/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191106-sqq5g/integration)
   * [summary.md](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191106-sqq5g/integration/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191106-sqq5g/integration/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.ozone.om.TestScmSafeMode](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestScmSafeMode.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestScmSafeMode-output.txt))

## unit check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/trunk/trunk-nightly-20191106-sqq5g/unit/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191106-sqq5g/unit)
   * [summary.md](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191106-sqq5g/unit/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191106-sqq5g/unit/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.ozone.om.TestKeyDeletingService](hadoop-ozone/ozone-manager/org.apache.hadoop.ozone.om.TestKeyDeletingService.txt) ([output](hadoop-ozone/ozone-manager/org.apache.hadoop.ozone.om.TestKeyDeletingService-output.txt))


# Tests with success status

## rat check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/trunk/trunk-nightly-20191106-sqq5g/rat/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191106-sqq5g/rat)


## checkstyle check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/trunk/trunk-nightly-20191106-sqq5g/checkstyle/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191106-sqq5g/checkstyle)


## findbugs check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/trunk/trunk-nightly-20191106-sqq5g/findbugs/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191106-sqq5g/findbugs)
   * [summary.html](https://elek.github.io/ozone-ci-03/trunk/trunk-nightly-20191106-sqq5g/findbugs/summary.html)


## checkout check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/trunk/trunk-nightly-20191106-sqq5g/checkout/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191106-sqq5g/checkout)


## build check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/trunk/trunk-nightly-20191106-sqq5g/build/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191106-sqq5g/build)


## author check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/trunk/trunk-nightly-20191106-sqq5g/author/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191106-sqq5g/author)




# References

 * All the results are saved to [here](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191106-sqq5g/)
 * The definition is the build is committed to [here](https://github.com/elek/argo-ozone)
    * The build is defined in [this argo workflow XML](https://github.com/elek/argo-ozone/blob/master/ozone-build.yaml)
    * This report is assembled by the [report script](https://github.com/elek/argo-ozone/blob/master/scripts/report.sh)

This is an experimental build and eventually can be merged to the Apache Hadoop Ozone source tree (after some testing).

In case of any question please contact with elek dot apache dot org.
