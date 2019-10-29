# Tests with failure status

## integration check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2375-drhps/integration/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2375-drhps/integration)
   * [summary.md](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2375-drhps/integration/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2375-drhps/integration/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.ozone.fsck.TestContainerMapper](hadoop-ozone/tools/org.apache.hadoop.ozone.fsck.TestContainerMapper.txt) ([output](hadoop-ozone/tools/org.apache.hadoop.ozone.fsck.TestContainerMapper-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestOzoneAtRestEncryption](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestOzoneAtRestEncryption.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestOzoneAtRestEncryption-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestOzoneRpcClientWithRatis](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestOzoneRpcClientWithRatis.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestOzoneRpcClientWithRatis-output.txt))
 * [org.apache.hadoop.ozone.container.TestContainerReplication](hadoop-ozone/integration-test/org.apache.hadoop.ozone.container.TestContainerReplication.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.container.TestContainerReplication-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestSecureOzoneRpcClient](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestSecureOzoneRpcClient.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestSecureOzoneRpcClient-output.txt))
 * [org.apache.hadoop.ozone.om.TestScmSafeMode](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestScmSafeMode.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestScmSafeMode-output.txt))
 * [org.apache.hadoop.ozone.scm.TestGetCommittedBlockLengthAndPutKey](hadoop-ozone/integration-test/org.apache.hadoop.ozone.scm.TestGetCommittedBlockLengthAndPutKey.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.scm.TestGetCommittedBlockLengthAndPutKey-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestOzoneRpcClient](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestOzoneRpcClient.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestOzoneRpcClient-output.txt))
 * [org.apache.hadoop.ozone.container.metrics.TestContainerMetrics](hadoop-ozone/integration-test/org.apache.hadoop.ozone.container.metrics.TestContainerMetrics.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.container.metrics.TestContainerMetrics-output.txt))
 * [org.apache.hadoop.ozone.container.ozoneimpl.TestOzoneContainer](hadoop-ozone/integration-test/org.apache.hadoop.ozone.container.ozoneimpl.TestOzoneContainer.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.container.ozoneimpl.TestOzoneContainer-output.txt))
 * [org.apache.hadoop.ozone.container.common.transport.server.ratis.TestCSMMetrics](hadoop-ozone/integration-test/org.apache.hadoop.ozone.container.common.transport.server.ratis.TestCSMMetrics.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.container.common.transport.server.ratis.TestCSMMetrics-output.txt))
 * [org.apache.hadoop.ozone.container.common.impl.TestContainerPersistence](hadoop-ozone/integration-test/org.apache.hadoop.ozone.container.common.impl.TestContainerPersistence.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.container.common.impl.TestContainerPersistence-output.txt))
 * [org.apache.hadoop.ozone.TestContainerStateMachineIdempotency](hadoop-ozone/integration-test/org.apache.hadoop.ozone.TestContainerStateMachineIdempotency.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.TestContainerStateMachineIdempotency-output.txt))

## checkstyle check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2375-drhps/checkstyle/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2375-drhps/checkstyle)
   * [summary.txt](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2375-drhps/checkstyle/summary.txt)

hadoop-hdds/client/src/main/java/org/apache/hadoop/hdds/scm/storage/CommitWatcher.java
 96: Line is longer than 80 characters (found 81).
 111: Line is longer than 80 characters (found 81).
hadoop-hdds/client/src/main/java/org/apache/hadoop/hdds/scm/storage/BlockOutputStream.java
 584: Line is longer than 80 characters (found 82).
hadoop-hdds/common/src/main/java/org/apache/hadoop/ozone/common/ChunkBuffer.java
 57: Line is longer than 80 characters (found 89).
 88: First sentence should end with a period.
 120: Line is longer than 80 characters (found 92).
 126: Line is longer than 80 characters (found 83).
hadoop-hdds/common/src/main/java/org/apache/hadoop/hdds/ratis/RatisHelper.java
 21: Unused import - java.io.DataOutputStream.
hadoop-ozone/integration-test/src/test/java/org/apache/hadoop/ozone/client/rpc/TestCommitWatcher.java
 156: Line is longer than 80 characters (found 89).
 232: Line is longer than 80 characters (found 89).


# Tests with success status

## unit check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2375-drhps/unit/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2375-drhps/unit)


## acceptance check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2375-drhps/acceptance/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2375-drhps/acceptance)
   * [summary.html](https://elek.github.io/ozone-ci-03/pr/pr-hdds-2375-drhps/acceptance/summary.html)


## rat check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2375-drhps/rat/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2375-drhps/rat)


## checkout check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2375-drhps/checkout/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2375-drhps/checkout)


## build check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2375-drhps/build/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2375-drhps/build)


## author check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2375-drhps/author/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2375-drhps/author)


## findbugs check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2375-drhps/findbugs/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2375-drhps/findbugs)
   * [summary.html](https://elek.github.io/ozone-ci-03/pr/pr-hdds-2375-drhps/findbugs/summary.html)




# References

 * All the results are saved to [here](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2375-drhps/)
 * The definition is the build is committed to [here](https://github.com/elek/argo-ozone)
    * The build is defined in [this argo workflow XML](https://github.com/elek/argo-ozone/blob/master/ozone-build.yaml)
    * This report is assembled by the [report script](https://github.com/elek/argo-ozone/blob/master/scripts/report.sh)

This is an experimental build and eventually can be merged to the Apache Hadoop Ozone source tree (after some testing).

In case of any question please contact with elek dot apache dot org.
