        <profile>
            <id>graph</id>
            <pluginRepositories>
                <pluginRepository>
                    <id>mvnplugins.fusesource.org</id>
                    <url>http://mvnplugins.fusesource.org/repo/release</url>
                    <releases>
                        <enabled>true</enabled>
                        <updatePolicy>always</updatePolicy>
                    </releases>
                </pluginRepository>
            </pluginRepositories>
            <build>
                <plugins>
                    <plugin>
                        <groupId>org.fusesource.mvnplugins</groupId>
                        <artifactId>maven-graph-plugin</artifactId>
                    </plugin>
                </plugins>
            </build>
        </profile>

mvn org.fusesource.mvnplugins:maven-graph-plugin:1.33-SNAPSHOT:reactor -Dhide-scope=test,provided -Dartifact-groupId=no.tine
