---

copyright:
  years:  2018, 2022
lastupdated: "2022-01-12"

keywords: Monitoring release notes, Monitoring updates

subcollection: monitoring

content-type: release-note

---

{{site.data.keyword.attribute-definition-list}}

# Release notes for {{site.data.keyword.mon_full_notm}}
{: #monitoring-release-notes}

Use these release notes to learn about the latest updates to {{site.data.keyword.mon_full}}.
{: shortdesc}

## 14 December 2021
{: #monitoring-dec1421}
{: release-note}

SMS event notification support
:   {{site.data.keyword.mon_full_notm}} now supports SMS notifications based on events.

## 2 November 2021
{: #monitoring-nov0221}
{: release-note}

Email event notification support
:   {{site.data.keyword.mon_full_notm}} now supports email notifications based on events.

## 30 September 2021
{: #monitoring-sep3021}
{: release-note}

Metrics streaming support
: You can use {{site.data.keyword.mon_full_notm}} to push a set of selected metrics to a Kafka service such as Event Streams. [Learn more about metric streaming](/docs/monitoring?topic=monitoring-data_streaming)

## 8 September 2021
{: #monitoring-sep0821}
{: release-note}

Secure support for new and updated compliance standards
:   New and updates compliance standards are supported.

    * Updates to PCI DSS V3.2.1.
    * New NIST 800-171 rev2 compliance.

## 31 August 2021
{: #monitoring-aug3121}
{: release-note}

Agent update
:   Added support for agent version 11.4.1. To see the the agent versions that are available, see the [monitoring agent Release Notes](https://docs.sysdig.com/en/sysdig-agent-release-notes.html){: external}.

## 12 August 2021
{: #monitoring-aug1221}
{: release-note}

Secure support for Inline Scanner
:   V2.4.6 is supported which adds support for images with manifest schema V1.

## 10 August 2021
{: #monitoring-aug1021}
{: release-note}

Monitoring integrations
:   You can monitor integrations using PromCat.

Alert enhancements
:   The following alert enhancements are available:

    * The alert library provides a recommended list of alerts you can configure based on the services running in your infrastructure.

    * The alerts page has been enhanced.  Visual cues have been added to identify alerts that have not been resolved.  Alerts can also be grouped based on the service they represent.

Dashboard enhancements
:   The following Kubernetes dashboard enhancements have been made:

    * Workload dashboards are refreshed.
    * Changes to the panel location and color coding.
    * Workflow simplification.
    * Improved capacity planning.
    * Easier to read text boxes.

## 30 July 2021
{: #monitoring-jul3021}
{: release-note}

Secure support for Inline Scanner
:   V2.4.5 is supported which fixes an issue when using `--verbose` with `--format json` resulting in corrupted JSON output.

## 28 July 2021
{: #monitoring-jul2821}
{: release-note}

Secure support for Inline Scanner
:   V2.4.4 is supported including the following updates:

    * Security fixes.
    * Adding a retry mechanism when pulling images from registries.
    * Adding the ability to write a JSON log to a file.
    * Fixed a malware scan issue.
    * Fixed issue when getting images for registries not supporting tag listing.

## 27 July 2021
{: #monitoring-jul2721}
{: release-note}

Secure support for Kubernetes Audit functionality 
:   General available support of Kubernetes Audit functionality as part of the Admission Controller. 

## 2 July 2021
{: #monitoring-jul0221}
{: release-note}

Secure support for Inline Scanner
:   V2.4.3 is supported including security fixes and a problem with incorrect version detection for Apache Struts 2.

## 1 July 2021
{: #monitoring-jul0121}
{: release-note}

Secure support for Node Image Analyzer
:   V0.1.13 is available.

## 14 June 2021
{: #monitoring-jun1421}
{: release-note}

Secure support for RedHat OpenShift Container Platform v4 benchmark
:   You can now scan and validate compliance with the controls included in the CIS benchmark requirements.

## 9 June 2021
{: #monitoring-jun0921}
{: release-note}

Secure change improvements to navigation and activity audit
:   Updates include:

    * Moving **Network** from under **Policies** in the menu.
    * Grouping **Activity Audit** and **Captures** into the **Investigation** menu item.
    * Runtime scope moved in **Activity Audit** to allow more space for activity data.
    * Activity types can be filtered directly from the graph.
    * Displayed element attributes can be filtered from the list.

## 4 June 2021
{: #monitoring-jun0421}
{: release-note}

Secure changes to Kubernetes network security configuration and user experience
:   Changes include:

    * New configuration panel allowing you to include or exclude a set of labels for a cluster or namespace.
    * Adding the ability to label IPs not mapped to Kubernetes or OpenShift entities.
    * Adding the ability to to configure internal subnets for clusters.
    * Adding additional information when hovering over a network connection or network node.
    * Adding unresolved IP filtering.
    * Adding **Network** as an item in the navigation.

## 1 June 2021
{: #monitoring-jun0121}
{: release-note}

PromQL library
:   A library of PromQL queries now available.

Prometheus remote write
:   Prometheus remote write support is now supported for ingesting metrics.

Improved dashboard templates
:   Dashboard templates have been improved for better data display and improved results.

## 27 May 2021
{: #monitoring-may2721}
{: release-note}

Secure beta support for Falco policy tuner 
:   A managed version of the Falco policy tuner is new available.

## 19 May 2021
{: #monitoring-may1921}
{: release-note}

Secure compliance support 
:   New compliance features for ISO27001:2013 and HIPAA are available.

Secure support for Inline Scanner
:   V2.4.1 is supported.

## 18 May 2021
{: #monitoring-may1821}
{: release-note}

Secure updates for new and improved host OS and container scanning tools
:   Functional updates include:

    * The ability to scan hosts in addition to container images.
    * Host benchmarks have been updated with additional checks and cluster aggregation.
    * Image scanning is updated to automatically scan images if they have not been scanned.

## 10 May 2021
{: #monitoring-may1021}
{: release-note}

Silencing alert notifications
:   You can silence alert notifications for a given scope or period of time.

New Kubernetes labels
:   The following labels have been added that can be used to scope dashboards and configure groups.

    * `kubernetes.workload.name`
    * `kubernetes.workload.type`

New Kubernetes dashboards
:   A number of new Kubernetes dashboards are available in beta.

## 29 April 2021
{: #monitoring-apr2921}
{: release-note}

Secure updates to scan results page
:   The layout of the scan results page has been reorganize to clearly distinguish policy evaluation from vulnerability matching and better summarize the information.

## 26 April 2021
{: #monitoring-apr2621}
{: release-note}

Extended label set
:   An extended label set is available for PromQL queries.

Microsoft Teams integration
:   You can use Microsoft Teams as a notification channel.

Capture files 
:   S3 compatible storage can be used for capture files.

Webhook channel integration
:   The following updates have been made to webhook integration:

    * TLS verification can be skipped.
    * The ability to add custom headers to append to the alert format.

Secure support for Inline Scanner
:   V2.4.0 is supported with the following changes:

    * Security fixes.
    * Addition of `HTTP_PROXY` and `HTTPS_PROXY` environment variables to retrieve the malware database inline behind a proxy.
    * Addition of support for the `.dockercfg` repository authorization method.
    * Use of HTTP1.1 by default.
    * Fix for when a Docker UID is not 1000.


## 31 March 2021
{: #monitoring-mar3121}
{: release-note}

CLI support
:   New CLI added that you can use to access information in {{site.data.keyword.mon_full_notm}}. [Learn more about the CLI](/docs/monitoring?topic=sysdig-monitor-cli-plugin-sysdig-monitor-cli).

API support
:   New API added that can be used to manage the {{site.data.keyword.mon_full_notm}} service. [Learn more about the API](/apidocs/monitor).

## 24 March 2021
{: #monitoring-mar2421}
{: release-note}

Secure beta support for image scanning reports
:   V3 of the image scanning reports is available in beta.  Functional changes include:

    * Allowing scheduling of reports and sending them through notification channels.
    * Allowing a preview of the report structure in the UI.
    * Adding an advanced query builder.
    * Adding more data columns and filters.
    * Adding two report types: vulnerability and policy.


## 22 March 2021
{: #monitoring-mar2221}
{: release-note}

Secure support for policy types
:   Policy types allows you to group policies into logical groups based on the sources used in the policy engine.

## 17 March 2021
{: #monitoring-mar1721}
{: release-note}

Secure UI enhancements and additional functionality
:   The following changes have been made:

    * Updates have been made to the scan results list.
    * New table design for the vulnerabilities list.  
    * Ability to open individual vulnerabilities and display additional information.

## 12 March 2021
{: #monitoring-mar1221}
{: release-note}

Secure deprecation
:  The following features are deprecated for Secure:

    * Commands Audit has been deprecated in favor of Activity Audit.
    * Policy Events is deprecated in favor of the Events feed.

## 3 March 2021
{: #monitoring-mar0321}
{: release-note}

PromQL query explorer
:   The PromQL query explorer helps you understand metrics and their labels and values and create queries even faster than before.

IBM Cloud Functions integration
:   IBM Cloud Functions can be used as a notification channel.

Persistence of dashboard scope
:   When returning to a previously visited dashboard, the last used scope will be retained.

## 2 March 2021
{: #monitoring-mar0221}
{: release-note}

Secure support for SOC 2, NIST 800-53 rev4 and rev5 regulatory compliance
:   SOC2, NIST 800-53 rev4 and NIST 800-53 rev5 standards have been added to the compliance feature.  New checks have also been added to the admission controller, network security policies, and node analyzer. 

## 23 February 2021
{: #monitoring-feb2321}
{: release-note}

Secure support for Windows scanning in beta
:   A beta version of Windows scanning is available as a standalone scanning engine.  No UI, management, or historical data is available.

Secure support for a UI-based admission controller
:   Kubernetes admission controlers define and customize the requests that are allowed on the cluster.  An admission controller intercepts and process requests to the Kubernetes API prior to persisting the object and after the request is authenticated.  Additional functionality is added to check images for common vulnerabilities and exposures (CVEs), misconfiguration, outdated images and so on.  Container images that do not meet the configured admission policies are rejected from the cluster before being allowed to run.


## 20 February 2021
{: #monitoring-feb2021}
{: release-note}

Secure support for CronJobs, Weave, and Cilium CNIs
:   The network security policy tool has been upgraded to add CronJob, Weave, and Cilium CNIs in addition to Calico support.

## 16 February 2021
{: #monitoring-feb1621}
{: release-note}

Secure support for multiple credentials
:   You can now assign multiple credentials to the same registry depending on the relative internal registry path that is used to pull the image.

## 10 February 2021
{: #monitoring-feb1021}
{: release-note}

Secure support for Inline Scanner
:   V2.3 is supported with the following changes:

    * Removes the prefixing of image names with `localbuild` when unneccessary.
    * Improved version detection for Logback, SpringFramework, and Tomcat Java.
    * Allows setting `openssl` using the `OPENSSL_SECLEVEL` environment variable to support old certificates.
    * Creation of a more robust image ID to avoid unnecessary image rescans.
    * Added malware detection. 

## 5 February 2021
{: #monitoring-feb0521}
{: release-note}

Importing Prometheus alert rules
:   You can now import Prometheus alert rules.

Dashboard enhancements
:   The following dashboard enhancements have been released:

    * You can edit the dashboard scope within the panel editor.
    * You can set a dashboard template as the team entry point.

## 4 February January 2021
{: #monitoring-feb0421}
{: release-note}

Secure support for enhanced activity audit filters
:   The noise-reduction filter has been improved to automatically filter duplicate entries in the feed with a high number of occurances.

## 31 January 2021
{: #monitoring-jan3121}
{: release-note}

Authentication token configuration
:   You can configure the authentication token that is allowed in a monitoring instance when you use Python scripts or the {{site.data.keyword.mon_short}} REST API to manage resources. By default, you can use an IAM token or a Monitoring API token. However, you can restrict the monitoring instance to only allow IAM tokens. [Learn more](/docs/monitoring?topic=monitoring-iam_instance_auth). 

## 28 January 2021
{: #monitoring-jan2821}
{: release-note}

Secure support for Node Image Analyzer
:   V0.1.9 is available with the following changes:

    * Added support for running the analyzer in non-Kubernetes environments.
    * Fixed an issue scanning images processed on GKE clusters using Docker and Containerd.
    * Fixed an issue that prevented images without full tags from being processed on OpenShift.
    * Improved version detection for Logback, SpringFramework, and Tomcat Java packages.
    * Fixed issues when an incorrect Docker socket path was provided.


## 5 January 2021
{: #monitoring-jan0521}
{: release-note}

Improved alerts
:   The alert interface has been improved for faster browsing and easier management.

## 23 December 2020
{: #monitoring-dec2320}
{: release-note}

Secure support for Jenkins
:   Plug-in V2.1 is available with the following changes:

    * Improved scanning performance and execution.
    * Proxy support for master and worker nodes.

## 16 December 2020
{: #monitoring-dec1620}
{: release-note}

Secure support for Node Image Analyzer
:   V0.1.7 is available.  This release fixes image analysis errors for OpenShift clusters configured in FIPS mode.

## 14 December 2020
{: #monitoring-dec1420}
{: release-note}

Secure support to scan images as a GitHub action
:   Support to do image analysis on locally built container images.

## 11 December 2020
{: #monitoring-dec1120}
{: release-note}

Secure support runtime policy events JSON format
:   A new JSON format for runtime policy events including full scope information, rule labels, and a single-line representation for event field keys and values.

## 7 December 2020
{: #monitoring-dec0720}
{: release-note}

Secure support for Node Image Analyzer
:   V0.1.6 is available with the following changes:

    * Proxy configuration support to run the analyzer behind a proxy.
    * Support to scan images without a `Repo` tag.

## 2 December 2020
{: #monitoring-dec0220}
{: release-note}

Secure support for inline scanner
:   V2.2 is available with the following changes:

    * Vulnerability report added to the container output.
    * Scanned images using the digest pullstring is stored using the truncated digest as a tag.
    * Users running other than as root have a permission issue resolved. 

## 23 November 2020
{: #monitoring-nov2320}
{: release-note}

Secure support for inline scanner
:   V2.1 is available with the following changes:

    * The ability to analyze scratch-based images.
    * Fixes for retrieved PDF output for previously scanned images. 
    * Fixes for container vulnerabilities.

## 20 November 2020
{: #monitoring-nov2020}
{: release-note}

Secure support
:   In architectures that are focused on container and microservices, you can use Secure to protect, monitor, and enhance forensic analysis of your pipeline and runtime components. [Learn more](/docs/monitoring?topic=monitoring-getting-started-secure)

## 19 November 2020
{: #monitoring-nov1920}
{: release-note}

Enhancements to Explore
:   A new grouping editor helps you create and manage infrastructure groupings.

Dashboard ownership
:   You can now transfer dashboard ownership to another user.

Dashboard enhancements
:   The following dashboard enhancements are now available:
  
    * The ability the dashboard menu to the sidebar.
    * The ability to specify your preference for open or closed categories.

## 27 July 2020
{: #monitoring-jul2720}
{: release-note}

Hosts overview
:   The hosts overview provides a view of the performance and health of the physical hosts in your infrastructure.

## 17 June 2020
{: #monitoring-jun1720}
{: release-note}

General availability of new dashboards
:   New functionality to improve the editing experience and add new ways to visualize and consume data.  Functional changes include:

    * Addition of a form-based and PromQL method of building dashboards.
    * Adding the ability to share dashboards with team members.
    * Customizing time series names and exes values on the legend.
    * The ability to configure multiple queries in a single panel.
    * Adding the ability to create a unified view of both metrics and events.
    * Availability of dashboard templates.
    * The ability to map values to text.

Limited availability of PromQL support
:   PromQL support for querying Prometheus metrics has been added for a subset of users.
    
Major functional changes
:   The following major changes are made in this release:

    * Topology maps are no longer available in dashboards.  Topology maps can be accessed through the **Explore** option.
    * **My Dashboards** are no longer available under **Explore**.
    * The dashboard wizard has been removed.  Use the dashboard templates in place of thd dashboard wizard.
    * History and summary metrics have been deprecated.
    * Ability to configure scope variables on a dashboard to quickly filter metrics.
    * Addition of intelligent auto-completion and syntax highlighting.
    * The ability to define a default role when a new member is added to a team.
    * Enhanced RBAC support.

## 16 April 2020
{: #monitoring-apr1620}
{: release-note}

Dashboard support for Istio 1.5
:   Addition of dashboard support for Istio 1.5, in addition to Istio 1.0.

## 21 November 2019
{: #monitoring-nov2119}
{: release-note}

Overview generally available
:   Functional enhancements include:

    * Metrics prioritized by event count and severity.
    * Dashboards for insights.
    * Added new default dashboards while retaining some existing dashboards and removing others.

Filtering events by scope
:    Events can be filtered by scope to show the most relevant events.  Filtering is available in the **Explore** and **Dashboards** views.

Beta support for Prometheus and new dashboards
:   Functional enhacements in beta include:

    * Support of native Prometheus time series ingestion.
    * Addition of a PromQL dashboard.
    * New dashboard functionality for greater configuration flexibility and query support.

## 11 October 2019
{: #monitoring-oct1119}
{: release-note}

Dashboard updates
:   The ability to mark a dashboard as a "favorite" has been added.

Additional metrics segmentation
:   The ability to segment metrics by the following have been added:

    * `file.bytes.in`
    * `file.bytes.out`
    * `file.mount`
    * `file.name`

## 14 August 2019
{: #monitoring-aug1419}
{: release-note}

New Kubernetes groupings
:   Groupings for Kubernetes have been modified.

Enhanced event notification
:   The ability to customize the subject and body of an alert notification with variables has been extended.

Units for metrics
:   Introduction of a common metrics format to ease comparison.

Display instance name
:   The instance name is now visible when creating and editing the instance name.

Kubernetes dashboard updates
:   Kubernetes cluster and node capacity dashboards now have actual CPU and memory usage compared to requests, limits, and capacity that can be allocated.

    In addition the Kubernetes health dashboard has been updated with metric aggregation across all containers running on the node.

## 11 July 2019
{: #monitoring-jul1119}
{: release-note}

Enhanced dashboard menu
:   Addition of a menu where you can add new dashboards and search for existing ones.

Customize alert notification template
:   Added the ability to customize messages sent with alert notifications.

Prometheus remote scraping
:   Added the ability to collect Prometheus metrics from remote endpoints.

Additional enhancements
:   The following additional enhancements were added.

    * Kafka integration support for authentication and SSL/TLS.

    * Addition of new Kubernetes metrics for pod counts.


## 1 December 2018
{: #monitoring-dec0118}
{: release-note}

Introducing {{site.data.keyword.mon_full_notm}}
:   {{site.data.keyword.mon_full}} is a cloud-native, and container-intelligence management system that you can include as part of your {{site.data.keyword.cloud_notm}} architecture. Use it to gain operational visibility into the performance and health of your applications, services, and platforms. It offers administrators, DevOps teams and developers full stack telemetry with advanced features to monitor and troubleshoot, define alerts, and design custom dashboards. In architectures that are focused on container and microservices, you can use Secure to protect, monitor, and enhance forensic analysis of your pipeline and runtime components.  [Learn more](/docs/monitoring?topic=monitoring-getting-started) 
