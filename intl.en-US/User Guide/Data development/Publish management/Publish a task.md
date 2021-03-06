# Publish a task {#concept_hhz_r2z_gfb .concept}

In a full data development process, developers develop code, debug processes, configure dependencies, configure scheduled tasks, and then submit tasks to the production environment for execution.

The [standard mode](../../../../../reseller.en-US/Product Introduction/Simple mode and standard mode.md#) of DataWorks can process data seamlessly from development to production stages in a project. We recommend that you use this mode for data development, production, and publishing.

## Publish a task in standard mode {#section_olf_dgz_gfb .section}

Each DataWorks project in the standard mode corresponds to two MaxCompute projects that are associated with one another, one for the development environment, and the other for the testing environment. You can submit and release a project to the production environment from the development environment.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/21852/155253327912963_en-US.jpg)

The procedure is as follows:

1.  Click **Submit** after the code and task is debugged and configured. The system will automatically check for dependencies between code objects.
2.  When the submission is completed, click **Publish**.
3.  Go to the To Publish page and select the target objects. Click **Add To Publish**, and the Publish List page appears.

    On the displayed Publish List page, you can filter the objects by publisher, node type, change type, publish date, and task name or ID. If you click **Publish Selected Items**, the objects are released to the production environment for scheduling immediately.

4.  Click **Open For Publish** \> **Publish All**to release the objects to the production environment.

    **Note:** The standard mode strictly prohibits operating the table data in the production environment. You can obtain a stable, secure, and reliable production environment. We strongly recommend that you use this mode to publish and schedule a task.


## Cross-project clone in simple mode {#section_fkr_rkz_gfb .section}

A simple mode project \(for development\) cannot publish tasks. To develop data and isolate the production environment, you must clone and then submit a task to a production project. This creates a simple mode project \(for production\).

As shown in the following figure, Simple Mode Project A is created for development and Simple Mode Project B for production. You can use **Cross-Project Cloning** to clone a task from Project A to Project B, and submit the clone to the scheduling engine for scheduling.

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/21852/155253327912977_en-US.jpg)

**Note:** 

-   Permission requirements: A RAM user account that is not the project owner requires administrative permissions, such as creating a clone package and publishing a clone task to run the operation and complete the process.
-   Supported subject types: Only tasks of a simple mode project can be cloned to other projects. The standard mode projects do not support this operation.
-   Prerequisites: The source project A \(a simple mode project\), and target project B \(a standard mode project\).

1.  Submit a task

    Select and submit the source task after it is edited.

2.  Click **Cross-Project Cloning**.
3.  Select the source task name in the list of submitted tasks and the target project name, click **Add For Clone**.
4.  Run a clone

    Click **For Cloning**. Check whether the source task information is correct and click **Clone All**.Click **Confirm** to run the operation and complete the clone process.

5.  View a cloned task

    You can view the successful tasks on the **Clone List** of source project A**Note:**View target project B to check whether the source task is cloned to the business flow.


