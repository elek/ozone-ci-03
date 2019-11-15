# Tests with failure status

## integration check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2442-bxv5b/integration/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2442-bxv5b/integration)
   * [summary.md](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2442-bxv5b/integration/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2442-bxv5b/integration/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.ozone.TestSecureOzoneCluster](hadoop-ozone/integration-test/org.apache.hadoop.ozone.TestSecureOzoneCluster.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.TestSecureOzoneCluster-output.txt))
 * [org.apache.hadoop.hdds.scm.pipeline.TestSCMPipelineManager](hadoop-ozone/integration-test/org.apache.hadoop.hdds.scm.pipeline.TestSCMPipelineManager.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.hdds.scm.pipeline.TestSCMPipelineManager-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestContainerStateMachine](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestContainerStateMachine.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestContainerStateMachine-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestFailureHandlingByClient](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestFailureHandlingByClient.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestFailureHandlingByClient-output.txt))

## acceptance check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2442-bxv5b/acceptance/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2442-bxv5b/acceptance)
   * [summary.html](https://elek.github.io/ozone-ci-03/pr/pr-hdds-2442-bxv5b/acceptance/summary.html)



# Tests with success status

## unit check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2442-bxv5b/unit/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2442-bxv5b/unit)


## rat check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2442-bxv5b/rat/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2442-bxv5b/rat)


## checkout check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2442-bxv5b/checkout/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2442-bxv5b/checkout)


## build check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2442-bxv5b/build/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2442-bxv5b/build)


## checkstyle check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2442-bxv5b/checkstyle/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2442-bxv5b/checkstyle)


## author check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2442-bxv5b/author/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2442-bxv5b/author)


## findbugs check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2442-bxv5b/findbugs/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2442-bxv5b/findbugs)
   * [summary.html](https://elek.github.io/ozone-ci-03/pr/pr-hdds-2442-bxv5b/findbugs/summary.html)




# References

 * All the results are saved to [here](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2442-bxv5b/)
 * The definition is the build is committed to [here](https://github.com/elek/argo-ozone)
    * The build is defined in [this argo workflow XML](https://github.com/elek/argo-ozone/blob/master/ozone-build.yaml)
    * This report is assembled by the [report script](https://github.com/elek/argo-ozone/blob/master/scripts/report.sh)

This is an experimental build and eventually can be merged to the Apache Hadoop Ozone source tree (after some testing).

In case of any question please contact with elek dot apache dot org.
