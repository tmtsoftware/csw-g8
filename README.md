# Giter8 Template for TMT

This is a Giter8 template for a TMT component developer which creates a sample `sbt` project for CSW Components.
The created project contains three subprojects:

- An Assembly
- An HCD
- A Deploy module, containing code to run the components

Use the following command to create a new project:
`sbt new tmtsoftware/csw.g8`

This template will prompt for the following parameters. Press Enter to accept the default values, shown in brackets:

- `name [sample]`: The name of the project.
- `assemblyComponentName [sample]` : The Component Name of the Assembly
- `hcdComponentName [sampleHcd]` : The Component Name of the HCD
- `organization [org.tmt]`: Specifies the organization for this project.
- `subsystem [CSW]`: Specifies the subsystem name.
- `version [0.0.1]`: Specifies the component version for this project.
- `package [org.tmt.csw]`: Top level package which dynamically gets created based on provided organization and subsystem in all subprojects.
- `deploy_module [sample-deploy]`: Subproject name which holds HostConfig and ContainerCmd applications.
- `assembly_module [sample]`: Subproject name which holds the Assembly code.
- `hcd_module [samplehcd]`: Subproject name which holds the HCD code.
- `scala_version [2.13.1]`: Specifies the Scala version for this project.
- `csw_version [2.0.1]`: Specifies the Common Software (CSW) version for this project.
