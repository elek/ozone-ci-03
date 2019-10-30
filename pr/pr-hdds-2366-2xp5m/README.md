# Tests with failure status

## checkstyle check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2366-2xp5m/checkstyle/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2366-2xp5m/checkstyle)
   * [summary.txt](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2366-2xp5m/checkstyle/summary.txt)

hadoop-ozone/integration-test/src/test/java/org/apache/hadoop/ozone/ozShell/TestOzoneDatanodeShell.java
 195: Redundant &apos;public&apos; modifier.

## acceptance check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2366-2xp5m/acceptance/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2366-2xp5m/acceptance)
   * [summary.html](https://elek.github.io/ozone-ci-03/pr/pr-hdds-2366-2xp5m/acceptance/summary.html)


## integration check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2366-2xp5m/integration/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2366-2xp5m/integration)
   * [summary.md](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2366-2xp5m/integration/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2366-2xp5m/integration/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.ozone.om.TestScmSafeMode](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestScmSafeMode.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestScmSafeMode-output.txt))


# Tests with success status

## rat check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2366-2xp5m/rat/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2366-2xp5m/rat)


## findbugs check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2366-2xp5m/findbugs/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2366-2xp5m/findbugs)
   * [summary.html](https://elek.github.io/ozone-ci-03/pr/pr-hdds-2366-2xp5m/findbugs/summary.html)


## checkout check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2366-2xp5m/checkout/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2366-2xp5m/checkout)


## build check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2366-2xp5m/build/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2366-2xp5m/build)


## author check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2366-2xp5m/author/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2366-2xp5m/author)


## unit check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-hdds-2366-2xp5m/unit/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2366-2xp5m/unit)




# References

 * All the results are saved to [here](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-hdds-2366-2xp5m/)
 * The definition is the build is committed to [here](https://github.com/elek/argo-ozone)
    * The build is defined in [this argo workflow XML](https://github.com/elek/argo-ozone/blob/master/ozone-build.yaml)
    * This report is assembled by the [report script](https://github.com/elek/argo-ozone/blob/master/scripts/report.sh)

This is an experimental build and eventually can be merged to the Apache Hadoop Ozone source tree (after some testing).

In case of any question please contact with elek dot apache dot org.
