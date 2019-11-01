# Tests with failure status

## rat check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2393-666mv/rat/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2393-666mv/rat)
   * [summary.txt](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2393-666mv/rat/summary.txt)

hadoop-hdds/common/target/rat.txt: !????? /workdir/hadoop-hdds/common/src/main/java/org/apache/hadoop/hdds/scm/ScmConfig.java

## checkstyle check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2393-666mv/checkstyle/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2393-666mv/checkstyle)
   * [summary.txt](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2393-666mv/checkstyle/summary.txt)

hadoop-hdds/server-scm/src/main/java/org/apache/hadoop/hdds/scm/server/StorageContainerManager.java
 508: Line is longer than 80 characters (found 89).
 509: &apos;ScmConfig&apos; has incorrect indentation level 8, expected level should be 10.
 509: Line is longer than 80 characters (found 88).
hadoop-hdds/server-scm/src/main/java/org/apache/hadoop/hdds/scm/server/StorageContainerManagerHttpServer.java
 65: Line is longer than 80 characters (found 84).
 69: Line is longer than 80 characters (found 82).
hadoop-hdds/server-scm/src/main/java/org/apache/hadoop/hdds/scm/server/SCMHTTPServerConfig.java
 29: Missing a Javadoc comment.
 42: Line is longer than 80 characters (found 100).
 42: &apos;{&apos; at column 62 should have line break after.
 48: Line is longer than 80 characters (found 96).
 50: Line is longer than 80 characters (found 88).
 50: &apos;{&apos; at column 56 should have line break after.
 52: &apos;{&apos; at column 40 should have line break after.
 54: &apos;{&apos; at column 37 should have line break after.
 55: Missing a Javadoc comment.
 56: Line is longer than 80 characters (found 100).
 58: Line is longer than 80 characters (found 85).
 60: Line is longer than 80 characters (found 105).
 61: Line is longer than 80 characters (found 104).
hadoop-hdds/common/src/main/java/org/apache/hadoop/hdds/protocolPB/SCMSecurityProtocolPB.java
 31: Line is longer than 80 characters (found 88).
hadoop-hdds/common/src/main/java/org/apache/hadoop/hdds/scm/protocol/StorageContainerLocationProtocol.java
 38: Line is longer than 80 characters (found 88).
hadoop-hdds/common/src/main/java/org/apache/hadoop/hdds/scm/protocol/ScmBlockLocationProtocol.java
 39: Line is longer than 80 characters (found 88).
hadoop-hdds/common/src/main/java/org/apache/hadoop/hdds/scm/ScmConfig.java
 8: Missing a Javadoc comment.
 14: &apos;type&apos; has incorrect indentation level 4, expected level should be 6.
 15: &apos;defaultValue&apos; has incorrect indentation level 4, expected level should be 6.
 16: &apos;tags&apos; has incorrect indentation level 4, expected level should be 6.
 17: &apos;description&apos; has incorrect indentation level 4, expected level should be 6.
 19: Line is longer than 80 characters (found 100).
 19: &apos;{&apos; at column 62 should have line break after.
 22: &apos;type&apos; has incorrect indentation level 4, expected level should be 6.
 23: &apos;defaultValue&apos; has incorrect indentation level 4, expected level should be 6.
 24: &apos;tags&apos; has incorrect indentation level 4, expected level should be 6.
 25: &apos;description&apos; has incorrect indentation level 4, expected level should be 6.
 25: Line is longer than 80 characters (found 89).
 27: Line is longer than 80 characters (found 88).
 27: &apos;{&apos; at column 56 should have line break after.
 29: &apos;{&apos; at column 40 should have line break after.
 31: &apos;{&apos; at column 37 should have line break after.
 33: Missing a Javadoc comment.
 34: Line is longer than 80 characters (found 100).
 36: Line is longer than 80 characters (found 85).
 38: Line is longer than 80 characters (found 95).
 39: Line is longer than 80 characters (found 99).
hadoop-hdds/common/src/main/java/org/apache/hadoop/hdds/protocol/SCMSecurityProtocol.java
 24: Unused import - org.apache.hadoop.hdds.scm.ScmConfigKeys.
hadoop-ozone/integration-test/src/test/java/org/apache/hadoop/ozone/TestSecureOzoneCluster.java
 210: Line is longer than 80 characters (found 82).
 211: Line is longer than 80 characters (found 99).
 239: Line is longer than 80 characters (found 85).
 254: Line is longer than 80 characters (found 93).
 271: &apos;SCMHTTPServerConfig&apos; has incorrect indentation level 6, expected level should be 8.

## acceptance check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2393-666mv/acceptance/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2393-666mv/acceptance)
   * [summary.html](https://elek.github.io/ozone-ci-03/pr/pr-hdds-2393-666mv/acceptance/summary.html)


## integration check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2393-666mv/integration/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2393-666mv/integration)
   * [summary.md](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2393-666mv/integration/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2393-666mv/integration/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.ozone.TestSecureOzoneCluster](hadoop-ozone/integration-test/org.apache.hadoop.ozone.TestSecureOzoneCluster.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.TestSecureOzoneCluster-output.txt))
 * [org.apache.hadoop.ozone.om.TestScmSafeMode](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestScmSafeMode.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestScmSafeMode-output.txt))
 * [org.apache.hadoop.ozone.TestOzoneConfigurationFields](hadoop-ozone/integration-test/org.apache.hadoop.ozone.TestOzoneConfigurationFields.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.TestOzoneConfigurationFields-output.txt))


# Tests with success status

## findbugs check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2393-666mv/findbugs/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2393-666mv/findbugs)
   * [summary.html](https://elek.github.io/ozone-ci-03/pr/pr-hdds-2393-666mv/findbugs/summary.html)


## checkout check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2393-666mv/checkout/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2393-666mv/checkout)


## build check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2393-666mv/build/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2393-666mv/build)


## author check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2393-666mv/author/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2393-666mv/author)


## unit check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2393-666mv/unit/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2393-666mv/unit)




# References

 * All the results are saved to [here](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2393-666mv/)
 * The definition is the build is committed to [here](https://github.com/elek/argo-ozone)
    * The build is defined in [this argo workflow XML](https://github.com/elek/argo-ozone/blob/master/ozone-build.yaml)
    * This report is assembled by the [report script](https://github.com/elek/argo-ozone/blob/master/scripts/report.sh)

This is an experimental build and eventually can be merged to the Apache Hadoop Ozone source tree (after some testing).

In case of any question please contact with elek dot apache dot org.
