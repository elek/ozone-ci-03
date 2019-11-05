# Tests with failure status

## checkstyle check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-master-hrht7/checkstyle/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-master-hrht7/checkstyle)
   * [summary.txt](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-master-hrht7/checkstyle/summary.txt)

hadoop-hdds/common/src/main/java/org/apache/hadoop/hdds/security/x509/certificates/utils/CertificateSignRequest.java
 28: Unused import - org.bouncycastle.asn1.ASN1Encodable.
 29: Unused import - org.bouncycastle.asn1.ASN1ObjectIdentifier.
 30: Unused import - org.bouncycastle.asn1.ASN1Sequence.
 31: Unused import - org.bouncycastle.asn1.ASN1TaggedObject.
 33: Unused import - org.bouncycastle.asn1.DERSequence.
 34: Unused import - org.bouncycastle.asn1.DERTaggedObject.
 43: Unused import - org.bouncycastle.asn1.x509.OtherName.
 212: Line is longer than 80 characters (found 99).
 215: Line is longer than 80 characters (found 90).
 216: Line is longer than 80 characters (found 89).

## acceptance check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-master-hrht7/acceptance/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-master-hrht7/acceptance)
   * [summary.html](https://elek.github.io/ozone-ci-03/pr/pr-master-hrht7/acceptance/summary.html)


## integration check is finished with failure status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-master-hrht7/integration/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-master-hrht7/integration)
   * [summary.md](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-master-hrht7/integration/summary.md)
   * [summary.txt](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-master-hrht7/integration/summary.txt)

# Failing tests: 

 * [org.apache.hadoop.ozone.om.TestScmSafeMode](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestScmSafeMode.txt) ([output](hadoop-ozone/integration-test/org.apache.hadoop.ozone.om.TestScmSafeMode-output.txt))


# Tests with success status

## rat check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-master-hrht7/rat/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-master-hrht7/rat)


## findbugs check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-master-hrht7/findbugs/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-master-hrht7/findbugs)
   * [summary.html](https://elek.github.io/ozone-ci-03/pr/pr-master-hrht7/findbugs/summary.html)


## checkout check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-master-hrht7/checkout/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-master-hrht7/checkout)


## build check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-master-hrht7/build/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-master-hrht7/build)


## author check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-master-hrht7/author/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-master-hrht7/author)


## unit check is finished with success status

   * [output](https://raw.githubusercontent.com/elek/ozone-ci-03/master/pr/pr-master-hrht7/unit/output.log)
   * [all collected results](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-master-hrht7/unit)




# References

 * All the results are saved to [here](https://github.com/elek/ozone-ci-03/tree/master/pr/pr-master-hrht7/)
 * The definition is the build is committed to [here](https://github.com/elek/argo-ozone)
    * The build is defined in [this argo workflow XML](https://github.com/elek/argo-ozone/blob/master/ozone-build.yaml)
    * This report is assembled by the [report script](https://github.com/elek/argo-ozone/blob/master/scripts/report.sh)

This is an experimental build and eventually can be merged to the Apache Hadoop Ozone source tree (after some testing).

In case of any question please contact with elek dot apache dot org.
