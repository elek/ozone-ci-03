# Tests with failure status

## integration check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/trunk/trunk-nightly-20191114-k5n9k/integration/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191114-k5n9k/integration)
   * [summary.md](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191114-k5n9k/integration/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191114-k5n9k/integration/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.ozone.freon.TestFreonWithPipelineDestroy](hadoop-ozone/tools/org.apache.hadoop.ozone.freon.TestFreonWithPipelineDestroy.txt) ([output](hadoop-ozone/tools/org.apache.hadoop.ozone.freon.TestFreonWithPipelineDestroy-output.txt))
 * [org.apache.hadoop.ozone.om.TestOzoneManagerHA](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestOzoneManagerHA.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestOzoneManagerHA-output.txt))
 * [org.apache.hadoop.ozone.TestSecureOzoneCluster](hadoop-ozone/integration-test/org.apache.hadoop.ozone.TestSecureOzoneCluster.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.TestSecureOzoneCluster-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestContainerStateMachine](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestContainerStateMachine.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestContainerStateMachine-output.txt))
 * [org.apache.hadoop.hdds.scm.pipeline.TestSCMPipelineManager](hadoop-ozone/integration-test/org.apache.hadoop.hdds.scm.pipeline.TestSCMPipelineManager.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.hdds.scm.pipeline.TestSCMPipelineManager-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestFailureHandlingByClient](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestFailureHandlingByClient.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestFailureHandlingByClient-output.txt))

## acceptance check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/trunk/trunk-nightly-20191114-k5n9k/acceptance/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191114-k5n9k/acceptance)
   * [summary.html](https://elek.github.io/ozone-ci-03/trunk/trunk-nightly-20191114-k5n9k/acceptance/summary.html)



# Tests with success status

## unit check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/trunk/trunk-nightly-20191114-k5n9k/unit/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191114-k5n9k/unit)


## rat check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/trunk/trunk-nightly-20191114-k5n9k/rat/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191114-k5n9k/rat)


## checkout check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/trunk/trunk-nightly-20191114-k5n9k/checkout/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191114-k5n9k/checkout)


## build check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/trunk/trunk-nightly-20191114-k5n9k/build/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191114-k5n9k/build)


## checkstyle check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/trunk/trunk-nightly-20191114-k5n9k/checkstyle/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191114-k5n9k/checkstyle)


## author check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/trunk/trunk-nightly-20191114-k5n9k/author/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191114-k5n9k/author)


## findbugs check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/trunk/trunk-nightly-20191114-k5n9k/findbugs/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191114-k5n9k/findbugs)
   * [summary.html](https://elek.github.io/ozone-ci-03/trunk/trunk-nightly-20191114-k5n9k/findbugs/summary.html)




# References

 * All the results are saved to [here](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191114-k5n9k/)
 * The definition is the build is committed to [here](https://github.com/elek/argo-ozone)
    * The build is defined in [this argo workflow XML](https://github.com/elek/argo-ozone/blob/master/ozone-build.yaml)
    * This report is assembled by the [report script](https://github.com/elek/argo-ozone/blob/master/scripts/report.sh)

This is an experimental build and eventually can be merged to the Apache Hadoop Ozone source tree (after some testing).

In case of any question please contact with elek dot apache dot org.
