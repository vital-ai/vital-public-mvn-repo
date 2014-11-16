vital-public-mvn-repo
=====================

vital ai public maven repo for artifacts

use the two branches here: "realeases" and "snapshots"

Can use this repo in maven POM with:
````
<repositories>
    <repository>
        <id>vital-public-mvn-repo-snapshots</id>
        <url>https://raw.github.com/vital-ai/vital-public-mvn-repo/snapshots</url>
        <snapshots>
            <enabled>true</enabled>
            <updatePolicy>always</updatePolicy>
        </snapshots>
    </repository>
</repositories>
````
