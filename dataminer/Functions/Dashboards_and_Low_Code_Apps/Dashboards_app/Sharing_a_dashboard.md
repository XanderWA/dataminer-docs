---
uid: Sharing_a_dashboard
---

# Sharing a dashboard

## Sharing a dashboard using the Live Sharing Service

> [!NOTE]
> This feature is only available if the DMA is [connected to dataminer.services](xref:Connecting_your_DataMiner_System_to_the_cloud).

1. In the list of dashboards on the left, select the dashboard you want to share.

1. Click the ... button in the top-right corner of the dashboard, and select *Share* or *Start sharing* (depending on your DataMiner version).

   > [!NOTE]
   >
   > - Make sure you have the appropriate [Live sharing user permissions](xref:DataMiner_user_permissions#general--live-sharing).
   > - Prior to DataMiner 10.2.0 [CU2]/10.2.5, to edit the dashboard, you need the user permission [Modules > Reports & Dashboards > Dashboards > Edit](xref:DataMiner_user_permissions#modules--reports--dashboards--dashboards--edit).
   > - If access to a dashboard is limited to some users only, it will not be possible to share the dashboard.

1. If you are using DataMiner 10.2.0/10.2.2 or higher, in the pop-up window, select *Create cloud share*. Otherwise, skip this step.

   ![Live Sharing Service](~/dataminer/images/Live_Sharing_Service.png)<br>*Live Sharing Service in DataMiner 10.4.5*

1. If it is the first time you are sharing the dashboard, you may be asked to confirm that you want to link your account to dataminer.services. Select *I want to link the above users* and click *Link accounts*.

1. In the pop-up window, fill in the email address(es) of the person(s) you want to share the dashboard with in the *With* field.

1. Optionally, add a description in the *Description* field.

1. Optionally, in the *Message* field, add a message you want to send to the person you are sharing the dashboard with, in order to provide additional information.

1. If you do not want the dashboard to remain permanently available, select *Add expiration date* and specify the expiration date.

1. Click *Share*. An email will be sent to the person you are sharing the dashboard with, to inform them that they now have access to the dashboard.

   ![Shared dashboard](~/dataminer/images/Shared_Dashboard.png)<br>*Live Sharing Service email in DataMiner 10.4.5*

> [!NOTE]
> At present, sharing dashboards that use the following components is not supported: spectrum components, Maps, SRM components (service definition and resource usage line graph), pivot tables, queries linked to data, and visualizations based on query data (e.g. node edge graph, table). For dashboards with queries that have the *Update data* setting enabled, sharing is supported from DataMiner 10.2.0 [CU4]/10.2.6 onwards. If you attempt to share a dashboard with content that is not supported for sharing, a message will be displayed with more information.

> [!TIP]
> See also: [Cloud connectivity and security](xref:Cloud_connectivity_and_security)

## Stopping a dashboard share

1. In the list of dashboards on the left, select the dashboard you want to stop sharing.

1. Click the *Shared* button in the dashboard header (available from DataMiner 10.3.5/10.4.0 onwards), or click the ... button in the top-right corner of the dashboard, and select *Manage share*.

   This will open a pop-up box where you can delete the share.

> [!NOTE]
> If you only want to update the message for the dashboard share, you can also do this via the *Shared* button or the *Manage share* option.

## Sharing a dashboard URL

From DataMiner 10.2.0/10.2.2 onwards, you can generate a URL to easily share a dashboard with other people who have the necessary rights to access it.

To do so:

### [From DataMiner 10.3.0 [CU12]/10.4.3 onwards](#tab/tabid-1)

1. In the list of dashboards on the left, select the dashboard<!--RN 38278-->.

1. Click the ... button in the top-right corner of the dashboard, and select *Share*.

1. To get a URL that only shows the dashboard without the rest of the app, enable the *Embed* option.

1. To get an uncompressed version of the URL, enable the *Use uncompressed URL parameters* option.

   > [!NOTE]
   > This option can for instance be useful if you want to embed the dashboard in a Visio drawing and use placeholders in the URL. See [Linking a shape to a webpage](xref:Linking_a_shape_to_a_webpage).

1. To the right of the URL, click the *Copy link* button.

### [Prior to DataMiner 10.3.0 [CU12]/10.4.3](#tab/tabid-2)

1. In the list of dashboards on the left, select the dashboard.

1. Click the ... button in the top-right corner of the dashboard, and select *Share*.

1. Click *URL*.

1. To get a URL that only shows the dashboard without the rest of the app, select *Embed*.

1. To get an uncompressed version of the URL, select *Use uncompressed URL parameters*.

   > [!NOTE]
   > This option can for instance be useful if you want to embed the dashboard in a Visio drawing and use placeholders in the URL. See [Linking a shape to a webpage](xref:Linking_a_shape_to_a_webpage).

1. To the right of the URL, click the *Copy* button.

***

## Sharing a dashboard as a PDF report via email

See [Sharing a dashboard as a PDF report from the Dashboards app](xref:Sharing_PDF_report_from_Dashboards_app).
