### Maven-Parent

## Maven Project Parent POM
This POM is the common parent of all of the Maven components in the Apache Maven project. Most of its contents are pinning down version numbers of plugins. 
It does provide minimal dependencyManagement for plexus-component and plugin-tools annotations.
This POM contains Maven developers information for the Project Team report, sorted by role and id. 
See the LDAP extract for more accurate committers and PMC members lists.

## Site Publication
This POM prepares site publication to Apache Maven's site svnpubsub. 
Every inheriting POM needs to define maven.site.path property with relative path to ${project.artifactId}-LATEST publication uri,
and define distributionManagement to avoid automatic inheritance from parent

