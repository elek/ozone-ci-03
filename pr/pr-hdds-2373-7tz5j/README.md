# Tests with failure status

## integration check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2373-7tz5j/integration/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2373-7tz5j/integration)
   * [summary.md](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2373-7tz5j/integration/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2373-7tz5j/integration/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.ozone.om.TestScmSafeMode](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestScmSafeMode.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestScmSafeMode-output.txt))

## checkstyle check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2373-7tz5j/checkstyle/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2373-7tz5j/checkstyle)
   * [summary.txt](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2373-7tz5j/checkstyle/summary.txt)

hadoop-hdds/client/src/main/java/org/apache/hadoop/hdds/scm/client/ContainerOperationClient.java
 96: &apos;xceiverClientManager&apos; hides a field.
hadoop-ozone/insight/src/main/java/org/apache/hadoop/ozone/insight/BaseInsightPoint.java
 21: Unused import - java.net.InetSocketAddress.
 27: Unused import - org.apache.hadoop.conf.StorageUnit.
 31: Unused import - org.apache.hadoop.hdds.scm.XceiverClientManager.
 34: Unused import - org.apache.hadoop.hdds.scm.protocol.StorageContainerLocationProtocol.
 35: Unused import - org.apache.hadoop.hdds.scm.protocolPB.StorageContainerLocationProtocolClientSideTranslatorPB.
 36: Unused import - org.apache.hadoop.hdds.scm.protocolPB.StorageContainerLocationProtocolPB.
 38: Unused import - org.apache.hadoop.hdds.tracing.TracingUtil.
 39: Unused import - org.apache.hadoop.ipc.Client.
 40: Unused import - org.apache.hadoop.ipc.ProtobufRpcEngine.
 41: Unused import - org.apache.hadoop.ipc.RPC.
 42: Unused import - org.apache.hadoop.net.NetUtils.
 43: Unused import - org.apache.hadoop.ozone.OzoneConsts.
 45: Unused import - org.apache.hadoop.security.UserGroupInformation.
 48: Unused import - org.apache.hadoop.hdds.HddsUtils.getScmAddressForClients.
 49: Unused import - org.apache.hadoop.hdds.scm.ScmConfigKeys.OZONE_SCM_CONTAINER_SIZE.
 50: Unused import - org.apache.hadoop.hdds.scm.ScmConfigKeys.OZONE_SCM_CONTAINER_SIZE_DEFAULT.


# Tests with success status

## unit check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2373-7tz5j/unit/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2373-7tz5j/unit)


## acceptance check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2373-7tz5j/acceptance/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2373-7tz5j/acceptance)
   * [summary.html](https://elek.github.io/ozone-ci-03/pr/pr-hdds-2373-7tz5j/acceptance/summary.html)


## rat check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2373-7tz5j/rat/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2373-7tz5j/rat)


## checkout check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2373-7tz5j/checkout/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2373-7tz5j/checkout)


## build check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2373-7tz5j/build/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2373-7tz5j/build)


## author check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2373-7tz5j/author/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2373-7tz5j/author)


## findbugs check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2373-7tz5j/findbugs/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2373-7tz5j/findbugs)
   * [summary.html](https://elek.github.io/ozone-ci-03/pr/pr-hdds-2373-7tz5j/findbugs/summary.html)




# References

 * All the results are saved to [here](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2373-7tz5j/)
 * The definition is the build is committed to [here](https://github.com/elek/argo-ozone)
    * The build is defined in [this argo workflow XML](https://github.com/elek/argo-ozone/blob/master/ozone-build.yaml)
    * This report is assembled by the [report script](https://github.com/elek/argo-ozone/blob/master/scripts/report.sh)

This is an experimental build and eventually can be merged to the Apache Hadoop Ozone source tree (after some testing).

In case of any question please contact with elek dot apache dot org.
