---

copyright:
  years: 2020, 2024

lastupdated: "2024-01-19"


keywords: satellite storage, change log, version history, ibm object storage plugin

subcollection: satellite

---

{{site.data.keyword.attribute-definition-list}}

# `ibm-object-storage-plugin` change log
{: #cl-ibm-object-storage-plugin}

Review the version history for the `ibm-object-storage-plugin` {{site.data.keyword.satelliteshort}} storage template.
{: shortdesc}

## Version 2.2
{: #ibm-object-storage-plugin-2.2-change-log}


### Revision 17, released 27 November 2023
{: #ibm-object-storage-plugin-2.2-rev-17-change-log}


- Resolves the following CVEs: [CVE-2007-4559](https://nvd.nist.gov/vuln/detail/CVE-2007-4559){: external} [CVE-2023-4016](https://nvd.nist.gov/vuln/detail/CVE-2023-4016){: external} [CVE-2023-4641](https://nvd.nist.gov/vuln/detail/CVE-2023-4641){: external} [CVE-2023-22745](https://nvd.nist.gov/vuln/detail/CVE-2023-22745){: external} [CVE-2023-40217](https://nvd.nist.gov/vuln/detail/CVE-2023-40217){: external} 
- Updates the UBI to version `8.9-1029`.
- Updates Go to version `1.21.4`.
- s3fs fuse version updated to v1.93

### Revision 16, released 30 October 2023
{: #ibm-object-storage-plugin-2.2-rev-16-change-log}


- Resolves the following CVEs: [CVE-2023-44487](https://nvd.nist.gov/vuln/detail/CVE-2023-44487){: external} [CVE-2023-39325](https://nvd.nist.gov/vuln/detail/CVE-2023-39325){: external} 
- Updates the UBI to version `8.8-1072.1697626218`.
- Updates Go to version `1.19.12`.

### Revision 15, released 18 October 2023
{: #ibm-object-storage-plugin-2.2-rev-15-change-log}


- Resolves the following CVEs: [CVE-2023-29491](https://nvd.nist.gov/vuln/detail/CVE-2023-29491){: external} [CVE-2023-4911](https://nvd.nist.gov/vuln/detail/CVE-2023-4911){: external} [CVE-2023-4527](https://nvd.nist.gov/vuln/detail/CVE-2023-4527){: external} [CVE-2023-4806](https://nvd.nist.gov/vuln/detail/CVE-2023-4806){: external} [CVE-2023-4813](https://nvd.nist.gov/vuln/detail/CVE-2023-4813){: external} 
- Updates the UBI to version `8.8-1072.1696517598`.
- Updates Go to version `1.19.12`.

### Revision 14, released 19 September 2023
{: #ibm-object-storage-plugin-2.2-rev-14-change-log}


- Resolves the following CVEs: [CVE-2023-27536](https://nvd.nist.gov/vuln/detail/CVE-2023-27536){: external} [CVE-2023-2602](https://nvd.nist.gov/vuln/detail/CVE-2023-2602){: external} [CVE-2023-2603](https://nvd.nist.gov/vuln/detail/CVE-2023-2603){: external} [CVE-2023-34969](https://nvd.nist.gov/vuln/detail/CVE-2023-34969){: external} [CVE-2023-28321](https://nvd.nist.gov/vuln/detail/CVE-2023-28321){: external} [CVE-2023-28484](https://nvd.nist.gov/vuln/detail/CVE-2023-28484){: external} [CVE-2023-29469](https://nvd.nist.gov/vuln/detail/CVE-2023-29469){: external} [CVE-2023-29409](https://nvd.nist.gov/vuln/detail/CVE-2023-29409){: external} 
- Updates the UBI to version `8.8-1037`.
- Updates Go to version `1.19.12`.
- RHCOS 4.13 support

### Revision 11, released 04 May 2023
{: #ibm-object-storage-plugin-2.2-rev-11-change-log}


- Resolves the following CVEs: [CVE-2023-24536](https://nvd.nist.gov/vuln/detail/CVE-2023-24536){: external} [CVE-2023-24537](https://nvd.nist.gov/vuln/detail/CVE-2023-24537){: external} [CVE-2023-24538](https://nvd.nist.gov/vuln/detail/CVE-2023-24538){: external} [CVE-2023-0361](https://nvd.nist.gov/vuln/detail/CVE-2023-0361){: external} 
- Updates the UBI to version `8.7-1107`.
- Updates Go to version `1.19.8`.
- Enable PVC metrics export to node stats

### Revision 10, released 04 April 2023
{: #ibm-object-storage-plugin-2.2-rev-10-change-log}


- Resolves the following CVEs: [CVE-2022-4304](https://nvd.nist.gov/vuln/detail/CVE-2022-4304){: external} [CVE-2022-4450](https://nvd.nist.gov/vuln/detail/CVE-2022-4450){: external} [CVE-2023-0215](https://nvd.nist.gov/vuln/detail/CVE-2023-0215){: external} [CVE-2023-0286](https://nvd.nist.gov/vuln/detail/CVE-2023-0286){: external} 
- Updates the UBI to version `8.7-1085.1679482090`.
- Updates Go to version `1.19.7`.
- Fix for helm chart installation failing on regions with no Regional COS endpoint 

### Revision 9, released 21 March 2023
{: #ibm-object-storage-plugin-2.2-rev-9-change-log}


- Resolves the following CVEs: [CVE-2023-23916](https://nvd.nist.gov/vuln/detail/CVE-2023-23916){: external} [CVE-2023-24532](https://nvd.nist.gov/vuln/detail/CVE-2023-24532){: external} 
- Updates the UBI to version `8.7-1085`.
- Updates Go to version `1.19.7`.
- Adds support to automatically populate the s3 endpoints for IBM, AWS, and Wasabi.

### Revision 8, released 06 March 2023
{: #ibm-object-storage-plugin-2.2-rev-8-change-log}


- Resolves the following CVEs: [CVE-2022-4415](https://nvd.nist.gov/vuln/detail/CVE-2022-4415){: external} [CVE-2020-10735](https://nvd.nist.gov/vuln/detail/CVE-2020-10735){: external} [CVE-2021-28861](https://nvd.nist.gov/vuln/detail/CVE-2021-28861){: external} [CVE-2022-45061](https://nvd.nist.gov/vuln/detail/CVE-2022-45061){: external} [CVE-2022-40897](https://nvd.nist.gov/vuln/detail/CVE-2022-40897){: external} [CVE-2022-41723](https://nvd.nist.gov/vuln/detail/CVE-2022-41723){: external} [CVE-2022-41724](https://nvd.nist.gov/vuln/detail/CVE-2022-41724){: external} 
- Updates the UBI to version `8.7-1085`.
- Updates Go to version `1.19.6`.

### Revision 7, released 20 February 2023
{: #ibm-object-storage-plugin-2.2-rev-7-change-log}


- Resolves the following CVEs: [CVE-2022-47629](https://nvd.nist.gov/vuln/detail/CVE-2022-47629){: external} 
- Updates the UBI to version `8.7-1049.1675784874`.
- Updates Go to version `1.18.9`.
- Sets the default values for CPU request and CPU limit to `100m` & `500m` respectively. 
- Sets the default values for Memory request and Memory limit are updated to `128Mi & 500Mi` respectively. 
- Adds an option to disable reading secret from cross namespace for PVC creation.
- Adds support for automatically populating the object store endpoint in the storage classes based on `storageclass` and `s3provider` parameters.
- Adds support for Wasabi & AWS s3 provider on Satellite clusters.


