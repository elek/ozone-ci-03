# Tests with failure status

## acceptance check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2482-j87dr/acceptance/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2482-j87dr/acceptance)
   * [summary.html](https://elek.github.io/ozone-ci-03/pr/pr-hdds-2482-j87dr/acceptance/summary.html)


## integration check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2482-j87dr/integration/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2482-j87dr/integration)
   * [summary.md](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2482-j87dr/integration/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2482-j87dr/integration/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.ozone.TestSecureOzoneCluster](hadoop-ozone/integration-test/org.apache.hadoop.ozone.TestSecureOzoneCluster.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.TestSecureOzoneCluster-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestContainerStateMachine](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestContainerStateMachine.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestContainerStateMachine-output.txt))
 * [org.apache.hadoop.hdds.scm.pipeline.TestSCMPipelineManager](hadoop-ozone/integration-test/org.apache.hadoop.hdds.scm.pipeline.TestSCMPipelineManager.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.hdds.scm.pipeline.TestSCMPipelineManager-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestFailureHandlingByClient](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestFailureHandlingByClient.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestFailureHandlingByClient-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestMultiBlockWritesWithDnFailures](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestMultiBlockWritesWithDnFailures.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestMultiBlockWritesWithDnFailures-output.txt))


# Tests with success status

## rat check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2482-j87dr/rat/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2482-j87dr/rat)


## checkstyle check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2482-j87dr/checkstyle/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2482-j87dr/checkstyle)


## findbugs check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2482-j87dr/findbugs/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2482-j87dr/findbugs)
   * [summary.html](https://elek.github.io/ozone-ci-03/pr/pr-hdds-2482-j87dr/findbugs/summary.html)


## checkout check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2482-j87dr/checkout/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2482-j87dr/checkout)


## build check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2482-j87dr/build/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2482-j87dr/build)


## author check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2482-j87dr/author/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2482-j87dr/author)


## unit check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2482-j87dr/unit/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2482-j87dr/unit)




# References

 * All the results are saved to [here](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2482-j87dr/)
 * The definition is the build is committed to [here](https://github.com/elek/argo-ozone)
    * The build is defined in [this argo workflow XML](https://github.com/elek/argo-ozone/blob/master/ozone-build.yaml)
    * This report is assembled by the [report script](https://github.com/elek/argo-ozone/blob/master/scripts/report.sh)

This is an experimental build and eventually can be merged to the Apache Hadoop Ozone source tree (after some testing).

In case of any question please contact with elek dot apache dot org.
