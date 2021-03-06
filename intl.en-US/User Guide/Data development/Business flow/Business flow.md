# Business flow {#concept_f3n_4nc_p2b .concept}

A business flow integrates different node task types by business type, such a structure improves business code development facilitation. The system organizes data development centered by the business flow, and provides container dashboards of various types of development nodes. In this way, tools, optimization operations, and management operations are arranged based on data dashboards objects, making development and management more convenient and intelligent.

## DataWorks code structure {#section_mdh_14c_p2b .section}

A work project supports multiple types of computing engines. A work project contains multiple business flows, each of which is a collection of various types of objects that are systematically associated with each other. You can view each business flow in the automatically generated flowcharts. Objects in a process can be any of the following types: data integration task, data development task, table, resource, function, algorithm, and operation flow.

Each object type corresponds to an independent folder, in which sub-folders can be created. To facilitate management, we recommend that you create a maximum of four layers of sub-folders. The planned business flow structure becomes too complex when more than four layers of sub-folders are created. We recommend that you split the business flow into one or more business flows and manage the related business flows in one solution. This business flow organization method is more efficient.

## Business flow composition {#section_qvx_k4c_p2b .section}

1.  Data Integration: For more information about Data Integration, see [Data integration node](reseller.en-US/User Guide/Data development/Node type/Data integration node.md#).
2.  Data Development: For more information about Data Integration, see [Node type overview](reseller.en-US/User Guide/Data development/Node type/Node types overview.md#).
3.  Table: For more information about Data Integration, see [Table Management](reseller.en-US/User Guide/Data development/Table Management.md#).
4.  Resources: For more information about Data Integration, see [Introduction to resources](reseller.en-US/User Guide/Data development/Business flow/Resource.md#).
5.  Functions: For more information about Data Integration, see [Introduction to functions](reseller.en-US/User Guide/Data development/Business flow/Register the UDFs.md#).

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/16288/15519377487640_en-US.png)

Double-click the name of a Business Flow node to view the relationship between nodes of the business flow in a workflow chart.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/16288/15519377497645_en-US.png)

## Business flow dashboard {#section_zqz_gvd_p2b .section}

You can check all business flows under a project on the business flow dashboard.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/16288/15519377497644_en-US.png)

## Business flow object dashboard {#section_z5c_zwd_p2b .section}

An object set dashboard is created for each object type in a business flow, and each object corresponds to an object card on the dashboard. You can attach the operation and optimization suggestions to the corresponding object, so that the object management is intelligent and convenient.

For example, on the object card of the data development task, the baseline strong protection and custom reminder icons are displayed, facilitating you to understand the current task protection status. You can double-click the icon of each object under the Business Flow to open the dashboard of the object type.

## Data Integration task dashboard {#section_if1_bxd_p2b .section}

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/16288/15519377497641_en-US.png)

## Data Development task dashboard {#section_azd_lxd_p2b .section}

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/16288/15519377497642_en-US.png)

**Note:** The number of nodes in a single business flow cannot exceed 100.

## Create a business flow {#section_fcg_rxd_p2b .section}

Right-click **Business Flow** under **Data Development**, select **Create Business Flow**.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/16288/15519377497643_en-US.png)

