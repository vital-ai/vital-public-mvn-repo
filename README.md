vital-public-mvn-repo
=====================

vital ai public maven repo for artifacts

use the two branches here: "realeases" and "snapshots"

Can use this repo in maven POM with:
````
<repositories>

    <repository>
        <id>vital-public-mvn-repo-snapshots</id>
        <name>Vital AI Public Maven Repo Snapshots</name>
        <url>https://github.com/vital-ai/vital-public-mvn-repo/raw/snapshots</url>
        <snapshots>
            <enabled>true</enabled>
            <updatePolicy>always</updatePolicy>
        </snapshots>
    </repository>
    
    <repository>
        <id>vital-public-mvn-repo-releases</id>
        <name>Vital AI Public Maven Repo Releases</name>
        <url>https://github.com/vital-ai/vital-public-mvn-repo/raw/releases/</url>
    </repository
    
</repositories>
````
