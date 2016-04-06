<build>
      <plugins>
        <plugin>
          <groupId>org.apache.maven.plugins</groupId>
          <artifactId>maven-jar-plugin</artifactId>
          <version>2.4</version>
          <configuration>
            <archive>
              <manifest>
                <addClasspath>true</addClasspath>
                <classpathPrefix>lib</classpathPrefix>
                <mainClass>project.App</mainClass>
              </manifest>
            </archive>
          </configuration>
        </plugin>
      </plugins>
  </build>
