# Tests with failure status

## checkstyle check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2301-n8986/checkstyle/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2301-n8986/checkstyle)
   * [summary.txt](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2301-n8986/checkstyle/summary.txt)

hadoop-ozone/ozone-manager/src/main/java/org/apache/hadoop/ozone/om/request/key/OMKeyRequest.java
 497: &apos;,&apos; is not followed by whitespace.
hadoop-ozone/ozone-manager/src/main/java/org/apache/hadoop/ozone/om/request/file/OMFileRequest.java
 27: Unused import - com.google.common.base.Preconditions.
 29: Unused import - org.apache.hadoop.ozone.om.exceptions.OMException.
 32: Unused import - org.apache.hadoop.ozone.om.helpers.OzoneFileStatus.
 36: Unused import - org.apache.hadoop.ozone.om.exceptions.OMException.ResultCodes.FILE_NOT_FOUND.
hadoop-ozone/ozone-manager/src/main/java/org/apache/hadoop/ozone/om/request/file/OMDirectoryCreateRequest.java
 201: &apos;,&apos; is not followed by whitespace.
hadoop-ozone/ozone-manager/src/main/java/org/apache/hadoop/ozone/om/request/file/OMFileCreateRequest.java
 149: Method length is 156 lines (max allowed is 150).
hadoop-ozone/ozone-manager/src/main/java/org/apache/hadoop/ozone/om/response/key/OMKeyCreateResponse.java
 76: Line is longer than 80 characters (found 88).
hadoop-ozone/ozone-manager/src/main/java/org/apache/hadoop/ozone/om/response/file/OMDirectoryCreateResponse.java
 77: Line is longer than 80 characters (found 88).
hadoop-ozone/ozone-manager/src/main/java/org/apache/hadoop/ozone/om/KeyManagerImpl.java
 1879: Expression can be simplified.
hadoop-ozone/ozonefs/src/test/java/org/apache/hadoop/fs/ozone/TestOzoneFileInterfaces.java
 43: Unused import - org.apache.hadoop.ozone.om.helpers.OzoneFSUtils.
 106: Variable &apos;bucket&apos; must be private and have accessor methods.
 349: First sentence should end with a period.
 382: Expression can be simplified.

## integration check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2301-n8986/integration/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2301-n8986/integration)
   * [summary.md](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2301-n8986/integration/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2301-n8986/integration/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.ozone.om.TestKeyManagerImpl](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestKeyManagerImpl.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestKeyManagerImpl-output.txt))
 * [org.apache.hadoop.ozone.ozShell.TestOzoneShellHA](hadoop-ozone/integration-test/org.apache.hadoop.ozone.ozShell.TestOzoneShellHA.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.ozShell.TestOzoneShellHA-output.txt))
 * [org.apache.hadoop.ozone.client.rpc.TestMultiBlockWritesWithDnFailures](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestMultiBlockWritesWithDnFailures.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.client.rpc.TestMultiBlockWritesWithDnFailures-output.txt))
 * [org.apache.hadoop.ozone.om.TestOzoneManagerHA](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestOzoneManagerHA.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestOzoneManagerHA-output.txt))
 * [org.apache.hadoop.fs.ozone.TestOzoneFileInterfaces](hadoop-ozone/ozonefs/org.apache.hadoop.fs.ozone.TestOzoneFileInterfaces.txt) ([output](hadoop-ozone/ozonefs/org.apache.hadoop.fs.ozone.TestOzoneFileInterfaces-output.txt))
 * [org.apache.hadoop.fs.ozone.contract.ITestOzoneContractOpen](hadoop-ozone/ozonefs/org.apache.hadoop.fs.ozone.contract.ITestOzoneContractOpen.txt) ([output](hadoop-ozone/ozonefs/org.apache.hadoop.fs.ozone.contract.ITestOzoneContractOpen-output.txt))
 * [org.apache.hadoop.fs.ozone.contract.ITestOzoneContractCreate](hadoop-ozone/ozonefs/org.apache.hadoop.fs.ozone.contract.ITestOzoneContractCreate.txt) ([output](hadoop-ozone/ozonefs/org.apache.hadoop.fs.ozone.contract.ITestOzoneContractCreate-output.txt))

## unit check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2301-n8986/unit/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2301-n8986/unit)
   * [summary.md](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2301-n8986/unit/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2301-n8986/unit/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.ozone.om.request.file.TestOMFileCreateRequest](hadoop-ozone/ozone-manager/org.apache.hadoop.ozone.om.request.file.TestOMFileCreateRequest.txt) ([output](hadoop-ozone/ozone-manager/org.apache.hadoop.ozone.om.request.file.TestOMFileCreateRequest-output.txt))


# Tests with success status

## rat check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2301-n8986/rat/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2301-n8986/rat)


## findbugs check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2301-n8986/findbugs/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2301-n8986/findbugs)
   * [summary.html](https://elek.github.io/ozone-ci-03/pr/pr-hdds-2301-n8986/findbugs/summary.html)


## checkout check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2301-n8986/checkout/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2301-n8986/checkout)


## build check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2301-n8986/build/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2301-n8986/build)


## acceptance check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2301-n8986/acceptance/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2301-n8986/acceptance)
   * [summary.html](https://elek.github.io/ozone-ci-03/pr/pr-hdds-2301-n8986/acceptance/summary.html)


## author check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2301-n8986/author/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2301-n8986/author)




# References

 * All the results are saved to [here](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2301-n8986/)
 * The definition is the build is committed to [here](https://github.com/elek/argo-ozone)
    * The build is defined in [this argo workflow XML](https://github.com/elek/argo-ozone/blob/master/ozone-build.yaml)
    * This report is assembled by the [report script](https://github.com/elek/argo-ozone/blob/master/scripts/report.sh)

This is an experimental build and eventually can be merged to the Apache Hadoop Ozone source tree (after some testing).

In case of any question please contact with elek dot apache dot org.
