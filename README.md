ParticleEffect [![](https://jitpack.io/v/sarhatabaot/ParticleEffect.svg)](https://jitpack.io/#sarhatabaot/ParticleEffect)
==============

This a library which allows you to display particle effects with Bukkit/Spigot. See http://bukkit.org/threads/1-8-particleeffect-v1-6.154406/ for more information about this project!

Documentation here: https://javadoc.jitpack.io/com/github/sarhatabaot/ParticleEffect/1.7.0-1.14.4/javadoc/

## Maven Dependency Information:
```xml
<repository>
	<id>jitpack.io</id>
	<url>https://jitpack.io</url>
</repository>
```
```xml        
<dependency>
	<groupId>com.github.shadowjonathan</groupId>
	<artifactId>ParticleEffect</artifactId>
	<version>1.7.1</version>
</dependency>
```
```xml      
<plugin>
     <groupId>org.apache.maven.plugins</groupId>
     <artifactId>maven-shade-plugin</artifactId>
     <version>3.2.1</version>
     <configuration>
        <relocations>
           <relocation>
                <pattern>com.darkblade12</pattern>
                <!-- Replace this with your package! -->
                <shadedPattern>your.package</shadedPattern>
           </relocation>
        </relocations>
     </configuration>
     <executions>
        <execution>
           <phase>package</phase>
            <goals>
              <goal>shade</goal>
            </goals>
        </execution>
     </executions>
</plugin>
```
