# Comandos Utilizados no POM
compile
test
package
clean

arquetypes project

mvn archetype:generate \
-DarchetypeGroupId=org.apache.maven.archetypes \
-DarchetypeArtifactId=maven-archetype-webapp \
-DarchetypeVersion=1.5 \
-DgroupId=com.meuprojeto \
-DartifactId=minha-app-web \
-DinteractiveMode=false

POM
Nome
dependencias
modulos
configuracoes de build
detalhes do projeto (licenca, url, etc)
configuracoes do ambiente

````xml
<project xmlns=url>
*   <modelVersion>...</modelVersion>
    
    The Basics
*   <groupId>...</groupId>
*   <artifactId>...</artifactId>
*   <version>...</version>
    <packaging>...</packaging>
    <dependencies>...</dependencies>
    <parent>...</parent>
    <dependencyManagement>...</dependencyManagement>
    <modules>...</modules>
    <properties>...</properties>

    Build Settings
    <build>...</build>
    <reporting>...</reporting>
    
    More Details
    <name>...</name>
    <description>...</description>
    <url>...</url>
    <inceptionYear>...</inceptionYear>
    <licenses>...</licenses>
    <organization>...</organization>
    <developers>...</developers>
    <contributors>...</contributors>
    
    Environment Settings
    <issueManagement>...</issueManagement>
    <ciManagement>...</ciManagement>
    <mailingLists>...</mailingLists>
    <scm>...</scm>
    <prerequisites>...</prerequisites>
    <repositories>...</repositories>
    <pluginRepositories>...</pluginRepositories>
    <distributionManagement>...</distributionManagement>
    <profiles>...</profiles>
    
</project>

`