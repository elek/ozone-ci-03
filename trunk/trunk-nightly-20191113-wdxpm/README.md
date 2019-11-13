# Tests with failure status

## integration check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/trunk/trunk-nightly-20191113-wdxpm/integration/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191113-wdxpm/integration)
   * [summary.md](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191113-wdxpm/integration/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191113-wdxpm/integration/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.ozone.freon.TestFreonWithPipelineDestroy](hadoop-ozone/tools/org.apache.hadoop.ozone.freon.TestFreonWithPipelineDestroy.txt) ([output](hadoop-ozone/tools/org.apache.hadoop.ozone.freon.TestFreonWithPipelineDestroy-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestMultiBlockWritesWithDnFailures](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestMultiBlockWritesWithDnFailures.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestMultiBlockWritesWithDnFailures-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestContainerStateMachine](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestContainerStateMachine.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestContainerStateMachine-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestFailureHandlingByClient](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestFailureHandlingByClient.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestFailureHandlingByClient-output.txt))
 * [org.apache.hadoop.hdds.scm.pipeline.TestSCMPipelineManager](hadoop-ozone/integration-test/org.apache.hadoop.hdds.scm.pipeline.TestSCMPipelineManager.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.hdds.scm.pipeline.TestSCMPipelineManager-output.txt))

## acceptance check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/trunk/trunk-nightly-20191113-wdxpm/acceptance/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191113-wdxpm/acceptance)
   * [summary.html](https://elek.github.io/ozone-ci-03/trunk/trunk-nightly-20191113-wdxpm/acceptance/summary.html)



# Tests with success status

## unit check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/trunk/trunk-nightly-20191113-wdxpm/unit/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191113-wdxpm/unit)


## rat check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/trunk/trunk-nightly-20191113-wdxpm/rat/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191113-wdxpm/rat)


## checkout check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/trunk/trunk-nightly-20191113-wdxpm/checkout/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191113-wdxpm/checkout)


## build check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/trunk/trunk-nightly-20191113-wdxpm/build/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191113-wdxpm/build)


## checkstyle check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/trunk/trunk-nightly-20191113-wdxpm/checkstyle/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191113-wdxpm/checkstyle)


## author check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/trunk/trunk-nightly-20191113-wdxpm/author/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191113-wdxpm/author)


## findbugs check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/trunk/trunk-nightly-20191113-wdxpm/findbugs/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191113-wdxpm/findbugs)
   * [summary.html](https://elek.github.io/ozone-ci-03/trunk/trunk-nightly-20191113-wdxpm/findbugs/summary.html)




# References

 * All the results are saved to [here](https://github.com/elek/ozone-ci-03/tree/master/trunk/trunk-nightly-20191113-wdxpm/)
 * The definition is the build is committed to [here](https://github.com/elek/argo-ozone)
    * The build is defined in [this argo workflow XML](https://github.com/elek/argo-ozone/blob/master/ozone-build.yaml)
    * This report is assembled by the [report script](https://github.com/elek/argo-ozone/blob/master/scripts/report.sh)

This is an experimental build and eventually can be merged to the Apache Hadoop Ozone source tree (after some testing).

In case of any question please contact with elek dot apache dot org.
