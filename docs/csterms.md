## Cloud Studio Terminology Guidelines

This is an internal document intended to help us refer to Cloud Studio
consistently and reinforce that terminology for both internal users and
customers. The external documents with full definitions and diagrams are
available at [Cloud Studio User
Interface](https://success.jitterbit.com/display/CS/Cloud+Studio+User+Interface)
and [Cloud Studio
Terminology](https://success.jitterbit.com/display/CS/Cloud+Studio+Terminology).

**NOTE:** Shortened forms should be used only in context. Do not use unless the
reference is obvious.

### General
-------

**project**: A collection of one or more workflows that comprise and execute an integration use case.

**project component** or (shorter) **component**: The discrete building blocks of a project. Some components, including activities, scripts, and transformations, can be added to operations that are executed as a sequence of steps. Other components can be used in support of those operations, such as variables, schedules, file schemas, notifications, and plugins. Operations themselves are also project components.
Do not use the terms **operation component**, **workflow component** or **design component**.

**workflow**: A collection of operations used as a tool to help segregate different parts of the project for the convenience of the user.

**operation**: The smallest unit within a workflow that is independently executed on an agent and recorded by Harmony. Operations define what an integration should do and when it should be done.

### Project Index

**project index** or (shorter) **index**: The page that provides a listing of all your Cloud Studio projects. Currently the landing page for Cloud Studio. Does not include Design Studio projects.

**project index card view** or (shorter) **card view**: One of two views for displaying projects in the project index. This view displays the projects as cards.Currently the default view. 

**project index cards** or (shorter) **project cards**, **index cards**, or **cards**: The project index card view displays projects as cards that can be flipped over to reveal details about the project.

**project index list view** or (shorter) **list view**: One of two views for displaying projects in the project index. This view displays the projects in a table.

### Project Designer

**project designer** or (shorter) **designer**: The design interface that displays after opening a project, including all three parts: project pane, design canvas, and design component palette. 
Do not use the terms **operation designer** or **workflow designer**.

**project pane** or (shorter) **pane**: The area on the left of the project designer that contains the project name, environment name, actions menu, and **Workflows** and **Components** tabs. 

**project navigator** or (shorter) **navigator**: The part of the project pane containing the **Workflows** and **Components** tabs, including the search and filter capabilities.

**project navigation tree** or (shorter) **navigation tree** or **tree*: The tree within either the **Workflows** or **Components** tab.

**Workflows** tab: One of two tabs available within the project navigator, focusing on individual workflows, their operations, and the steps used to execute those operations.

| **Components** tab: One of two tabs available within the project navigator, showing all project components and identifying whether they are used in support of an operation. 

**design canvas** or (shorter) **canvas**: The central area of the project designer serving as the primary workspace where you visually design your integrations. Do not use the terms **project canvas**, **workflow canvas**, or **operation canvas**.

**design canvas elements** or (shorter) **canvas elements**, **design elements**: Anything that is directly visible on the canvas outside of an operation, such as an email component or operation action lines.

**operation steps** or (shorter) **steps** or (longer) **steps of an operation**: The discrete components that make up an operation and are represented by component blocks (scripts, activities, transformations).Do not use the term **operation components*. If you are referring to components used in support of an operation, state so explicitly or use the term **project components**.)
****
**design component palette** or (shorter) **component palette**, **design palette**, or **palette**: The area on the right of the project designer that provides access to project components that can be used on the design canvas. Do not use the term **connectivity palette**. Currently, this palette contains only one tab providing access to connectivity resources. As this will be expanded on in the future, we should avoid referring to this as a connectivity **palette.

### Design Component Palette
-
**Connectivity** tab: The tab within the design component palette that provides access to connectivity resources. Within this tab, connectors are first configured to create connections. Activities associated with those connections can then be added to operations on the design canvas and configured as sources or targets. An endpoint refers to a specific connection and its activities.
Currently there is only one tab. If you have an issue referring to a tab when multiple tabs are present, reword to avoid this reference. For example: *the design component palette provides access to connectivity resources*. 

**connector**: Provides the interface for entering user-provided input such as credentials to create an authenticated connection. The **Connectors** filter shows the types of connectors that can be configured. In addition, you can create custom connectors using Connector Builder or the Connector SDK.

**connection**: Authenticated access to a data resource that has been configured using a connector. The **Endpoints** filter shows these configured connections. Existing connections can be edited by double-clicking on the connection in the palette.

**activity**: An interaction with a connection that can be configured with user-provided input such as data structures that represent the "request" and "response" schemas for that action. The **Endpoints** filter shows the configured connections, which can be clicked to reveal the types of activities that can be added to an operation. Those activities are then able to be dragged to operations on the design canvas, where they can be configured by double-clicking on the activity within the operation. Configured activities can act as sources (providing data within an operation) or targets (receiving data within an operation).

**endpoint** A specific connection and its activities, which are added to an operation and then configured as sources or targets within the operation.

### Scripts and Transformations

**script**: Scripts, written in either Jitterbit Script or JavaScript, provide the flexibility and power to transform data, perform calculations, or perform logic validation beyond simple field mapping.

**transformation**: A project component that is used as a step in an operation to map or *transform* inputs to a resulting output by moving data, cleaning data, or applying business logic. A transformation consists of source and target schemas that have been defined in the transformation and the transformation mapping that generates the output


**transformation mapping**: A transformation mapping consists of target fields or nodes and their corresponding scripts. These scripts may contain references to source fields or nodes or to project components, use functions, or contain other valid script logic. A mapping does *not* include target fields that are not mapped.

**script component palette** or (shorter) **component palette**, **script palette**, **palette**: The area on the right of the script and script mode transformation configuration screens that provides access to functions and project components that can be used within scripts. The script palette on the transformation screen includes access to an additional tab, **Source Objects**.
Refer to each tab by its appropriate name, as labeled in the product. 

**mapping mode**: A display mode for viewing or editing a transformation. This mode provides a visual overview of the mapping and the basic tools to perform the mapping. This is the default mode.

**script mode**:  A display mode for viewing or editing a transformation. This mode provides detailed views of fields and advanced tools for adding scripts to the mapping.