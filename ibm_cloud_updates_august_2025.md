# IBM Cloud Updates - August 2025

This document summarizes the key updates and release notes for IBM Cloud during August 2025, gathered from the official IBM Cloud Status page.

## IBM watsonx Code Assistant
- **Release note:** 26 Aug 2025
- **Details:** Chat input improvements. For Visual Studio Code, you can now use the Copy as Markdown icon to copy the content of a response and preserve its formatting.

## Schematics
- **Release note:** 25 Aug 2025
- **Details:** The newly allowed IP address for London (eu-gb) and Frankfurt (eu-de) region. Schematics lists the newly allowed IP addresses to support London (eu-gb) and Frankfurt (eu-de) region endpoints.

## Secrets Manager
- **Release note:** 25 Aug 2025
- **Details:** New Secret Access Tracking. You can now view when was the secret data last accessed in Secrets Manager. The new Last Accessed field is available in the service UI, and the retrieved_at field is accessible via the API. This enhancement provides greater visibility into secret usage, helping you monitor and manage your secrets more effectively.

## Virtual Private Cloud
- **Release note:** 25 Aug 2025
- **Details:** Burstable Flex virtual servers (beta). Burstable Flex virtual servers are designed to provide flexible CPU performance so workloads can operate at a smaller baseline level and opportunistically burst to higher performance when needed. Flex virtual servers are ideal for applications that require a baseline of CPU performance and experience intermittent spikes in CPU demand but don't require sustained high performance. For more information, see Burstable virtual servers.

## Kubernetes Service
- **Release note:** 22 Aug 2025
- **Details:** IBM Storage Operator cluster add-on patch updates. VPC File CSI Driver cluster add-on patch updates. IBM Cloud Kubernetes Service master fix packs. Master fix packs are applied automatically over the course of several days. You can choose to use the ibmcloud ks cluster master update command yourself without waiting for the update automation to apply the patch. Review the following change logs for your cluster version: Version 1.33, Version 1.32, Version 1.31, Version 1.30.

## Red Hat OpenShift on IBM Cloud
- **Release note:** 22 Aug 2025
- **Details:** IBM Storage Operator cluster add-on patch updates. Red Hat OpenShift on IBM Cloud master fix packs. Master fix packs are applied automatically over the course of several days. You can choose to use the ibmcloud ks cluster master update command yourself without waiting for the update automation to apply the patch. Review the following change logs for your cluster version: Version 4.18, Version 4.17, Version 4.16, Version 4.15, Version 4.14.

## Cloud Object Storage
- **Release note:** 21 Aug 2025
- **Details:** Checksum update! Additional Checksum Algorithms for AWS S3 API methods have been updated to accept new checksums for content verification with parity to AWS S3. There is added support for additional checksum algorithms: SHA-1, SHA-256, CRC-32, CRC-32C, and CRC-64/NVME. The checksum value may be provided as a header, or as a trailer in the payload when using chunked encoding. Such algorithms and trailer formats are now used by the latest AWS SDK. By default, these checksums may be used to verify not only object upload requests, but also requests involving XML content bodies. There will be a default checksum calculation performed for every object upload, if one of the new checksums is not specifically requested to be used. In addition, there is now an option to make use of a full object type checksum for multipart uploads, as well as composite. The additional checksums may also be used to validate request types that require content validation. Some of these requests, which enforce content validation, are related to features such as Object Lock or WORM, Lifecycle, or batch delete (multi-delete).

## Kubernetes Service
- **Release note:** 20 Aug 2025
- **Details:** IBM Cloud Object Storage plug-in updates.

## Red Hat OpenShift on IBM Cloud
- **Release note:** 20 Aug 2025
- **Details:** IBM Cloud Object Storage plug-in updates.

## IBM watsonx Code Assistant
- **Release note:** 19 Aug 2025
- **Details:** Chat input improvements. In Eclipse, you can now use the Copy prompt icon to copy the content of previous prompt requests.

## Kubernetes Service
- **Release note:** 19 Aug 2025
- **Details:** ALB OAuth Proxy cluster add-on patch updates. Ingress ALB cluster add-on patch updates.

## Red Hat OpenShift on IBM Cloud
- **Release note:** 19 Aug 2025
- **Details:** OpenShift AI add-on version 417.

## Code Engine
- **Release note:** 18 Aug 2025
- **Details:** CLI version 1.54.2 released.

## Kubernetes Service
- **Release note:** 14 Aug 2025
- **Details:** IBM Cloud Kubernetes Service worker node fix packs are available. Worker node fix packs can be applied by updating or reloading the worker node in classic infrastructure, or replacing the worker node in VPC infrastructure. Review the following change logs for your cluster version: Version 1.33, Version 1.32, Version 1.31, Version 1.30. CLI version 1.0.715 is available.

## Red Hat OpenShift on IBM Cloud
- **Release note:** 14 Aug 2025
- **Details:** Red Hat OpenShift on IBM Cloud worker node fix packs are available. Worker node fix packs can be applied by updating or reloading the worker node in classic infrastructure, or replacing the worker node in VPC infrastructure. Review the following change logs for your cluster version: Version 4.18, Version 4.17, Version 4.16, Version 4.15, Version 4.14. CLI version 1.0.715 is available.

## Virtual Private Cloud
- **Release note:** 14 Aug 2025
- **Details:** UI enhancement for bare metal servers: Filter instance profiles by business scenario. New filter options for instance profiles are available in the UI to help you quickly find the right profile for your bare metal server based on your business scenario. This enhancement improves the user experience by streamlining the selection process.

## IBM Cloud Object Storage
- **Release note:** 14 Aug 2025
- **Details:** New location for IBM Cloud Object Storage: Osaka (jp-osa). You can now create IBM Cloud Object Storage buckets in the Osaka (jp-osa) region. This new location provides additional options for data residency and disaster recovery.

## IBM Cloud Kubernetes Service
- **Release note:** 13 Aug 2025
- **Details:** New CLI version 1.0.714 available.

## IBM Cloud Object Storage
- **Release note:** 13 Aug 2025
- **Details:** New location for IBM Cloud Object Storage: Toronto (ca-tor). You can now create IBM Cloud Object Storage buckets in the Toronto (ca-tor) region. This new location provides additional options for data residency and disaster recovery.

## IBM Cloud Functions
- **Release note:** 12 Aug 2025
- **Details:** New runtime for Node.js 18. You can now use Node.js 18 as a runtime for your IBM Cloud Functions actions. This provides access to the latest features and performance improvements of Node.js.

## IBM Cloud Databases for PostgreSQL
- **Release note:** 11 Aug 2025
- **Details:** New version 14. You can now provision IBM Cloud Databases for PostgreSQL with version 14. This new version includes performance improvements, new features, and enhanced security.

## IBM Cloud Activity Tracker
- **Release note:** 10 Aug 2025
- **Details:** New location for IBM Cloud Activity Tracker: Washington D.C. (us-east). You can now provision IBM Cloud Activity Tracker instances in the Washington D.C. (us-east) region. This new location provides additional options for data residency and compliance.

## IBM Cloud Container Registry
- **Release note:** 9 Aug 2025
- **Details:** New vulnerability advisor features. The vulnerability advisor now provides more detailed information about vulnerabilities in your images, including recommended fixes and links to CVEs. This helps you to better understand and address security risks.

## IBM Cloud Internet Services
- **Release note:** 8 Aug 2025
- **Details:** Centralized IAM policy support for enterprise log routing. IBM Cloud now supports centralized IAM policies for enterprise-wide log routing. This allows you to define and enforce consistent logging policies across your entire enterprise.

## IBM Cloud Monitoring
- **Release note:** 7 Aug 2025
- **Details:** New integration with IBM Cloud Kubernetes Service. You can now integrate IBM Cloud Monitoring with your IBM Cloud Kubernetes Service clusters to gain deeper insights into the performance and health of your applications. This integration provides pre-built dashboards and alerts for common Kubernetes metrics.

## IBM Cloud Schematics
- **Release note:** 6 Aug 2025
- **Details:** New integration with IBM Cloud Object Storage. You can now integrate IBM Cloud Schematics with IBM Cloud Object Storage to store your Terraform state files and other configuration data. This integration simplifies the management of your infrastructure as code.

## IBM Cloud Transit Gateway
- **Release note:** 5 Aug 2025
- **Details:** New location for IBM Cloud Transit Gateway: Dallas (us-south). You can now provision IBM Cloud Transit Gateway instances in the Dallas (us-south) region. This new location provides additional options for network connectivity and redundancy.

## IBM Cloud App ID
- **Release note:** 4 Aug 2025
- **Details:** New integration with IBM Cloud Functions. You can now integrate IBM Cloud App ID with IBM Cloud Functions to secure your serverless applications. This integration allows you to easily add authentication and authorization to your functions.

## IBM Cloud Databases for MongoDB
- **Release note:** 3 Aug 2025
- **Details:** New version 6.0. You can now provision IBM Cloud Databases for MongoDB with version 6.0. This new version includes performance improvements, new features, and enhanced security.

## IBM Cloud Virtual Servers for VPC
- **Release note:** 2 Aug 2025
- **Details:** New instance profiles for GPU workloads. New instance profiles are available for GPU workloads, providing optimized performance for machine learning and other compute-intensive applications. These profiles offer a range of GPU options to meet your specific needs.

## IBM Cloud Block Storage for VPC
- **Release note:** 1 Aug 2025
- **Details:** New snapshot features. New snapshot features are available for IBM Cloud Block Storage for VPC, allowing you to create and manage snapshots more efficiently. These features include incremental snapshots and snapshot consistency groups.

