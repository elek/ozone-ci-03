# Tests with failure status

## integration check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/dev/dev-testrun-4rklj/integration/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/dev/dev-testrun-4rklj/integration)
   * [summary.md](https://github.com/elek/ozone-ci-03/tree/master/dev/dev-testrun-4rklj/integration/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-03/tree/master/dev/dev-testrun-4rklj/integration/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.ozone.client.rpc.TestDeleteWithSlowFollower](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestDeleteWithSlowFollower.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestDeleteWithSlowFollower-output.txt))
 * [org.apache.hadoop.ozone.om.TestOzoneManagerHA](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestOzoneManagerHA.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestOzoneManagerHA-output.txt))
 * [org.apache.hadoop.ozone.om.TestScmSafeMode](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestScmSafeMode.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestScmSafeMode-output.txt))

## acceptance check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/dev/dev-testrun-4rklj/acceptance/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/dev/dev-testrun-4rklj/acceptance)
   * [summary.html](https://elek.github.io/ozone-ci-03/dev/dev-testrun-4rklj/acceptance/summary.html)


## unit check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/dev/dev-testrun-4rklj/unit/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/dev/dev-testrun-4rklj/unit)



# Tests with success status

## checkstyle check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/dev/dev-testrun-4rklj/checkstyle/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/dev/dev-testrun-4rklj/checkstyle)


## findbugs check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/dev/dev-testrun-4rklj/findbugs/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/dev/dev-testrun-4rklj/findbugs)
   * [summary.html](https://elek.github.io/ozone-ci-03/dev/dev-testrun-4rklj/findbugs/summary.html)


## checkout check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/dev/dev-testrun-4rklj/checkout/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/dev/dev-testrun-4rklj/checkout)


## author check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/dev/dev-testrun-4rklj/author/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/dev/dev-testrun-4rklj/author)


## build check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/dev/dev-testrun-4rklj/build/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/dev/dev-testrun-4rklj/build)


## rat check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/dev/dev-testrun-4rklj/rat/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/dev/dev-testrun-4rklj/rat)




# References

 * All the results are saved to [here](https://github.com/elek/ozone-ci-03/tree/master/dev/dev-testrun-4rklj/)
 * The definition is the build is committed to [here](https://github.com/elek/argo-ozone)
    * The build is defined in [this argo workflow XML](https://github.com/elek/argo-ozone/blob/master/ozone-build.yaml)
    * This report is assembled by the [report script](https://github.com/elek/argo-ozone/blob/master/scripts/report.sh)

This is an experimental build and eventually can be merged to the Apache Hadoop Ozone source tree (after some testing).

In case of any question please contact with elek dot apache dot org.
