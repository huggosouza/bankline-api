# Bankline API

A REST API using Spring Boot, hibernate, JPA, Maven etc.

I needed to add these lines:

  <plugin>
      <groupId>org.apache.maven.plugins</groupId>
      <artifactId>maven-compiler-plugin</artifactId>
      <configuration>
          <source>1.8</source>
          <target>1.8</target>
       </configuration>
  </plugin>
  
in pom.xml so I could build it on Heroku. You probably ain't going to need this if you're not deploying to Heroku.

I've written this code in Santander Dev Week Bootcamp, so I haven't done anything alone, I've acquired many experience with it and understood many concepts I wasn't familiriazed yet and I'm very happy with it.
