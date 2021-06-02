# Spring-MVC (PetPeer Web Application)
**STEPS TO BUILD THE APPLICATION ARE AS FOLLOWS**
**Step-1** Create a Maven Project under Eclipse IDE. Give the Group-id, Artifact-id(Project Name), Package Name and the packaging as war. In our project these are the names.
                      <groupId>com.casestudy</groupId>
	                    <artifactId>PetPeersWebApp</artifactId>
	                    <packaging>war</packaging>
                      <finalName>PetPeersWebApp</finalName>
                      
**Step-2** In the Target Folder there is a pom.xml file add all the necessary dependencies there.
  <properties>
		<project.build.sourceEncoding>UTF-8</project.build.sourceEncoding>
		<maven.compiler.source>1.8</maven.compiler.source>
		<maven.compiler.target>1.8</maven.compiler.target>
		<spring.version>4.3.2.RELEASE</spring.version>
		<junit.version>4.12</junit.version>
		<servlet.version>3.1.0</servlet.version>
		<servlet.version>3.0.1</servlet.version>
		<mysql.connector.version>5.1.9</mysql.connector.version>
	</properties>
	<dependencies>
		<!--Servlet-Api -->
		<dependency>
			<groupId>javax.servlet</groupId>
			<artifactId>javax.servlet-api</artifactId>
			<version>${servlet.version}</version>
		</dependency>
		<!-- Spring Core Framework -->
		<dependency>
			<groupId>org.springframework</groupId>
			<artifactId>spring-core</artifactId>
			<version>${spring.version}</version>
		</dependency>
		<dependency>
      <!-- Spring-Beans Framework -->
			<groupId>org.springframework</groupId>
			<artifactId>spring-beans</artifactId>
			<version>${spring.version}</version>
		</dependency>
		<dependency>
      <!-- Spring-Context Framework -->
			<groupId>org.springframework</groupId>
			<artifactId>spring-context</artifactId>
			<version>${spring.version}</version>
		</dependency>
		<dependency>
			<groupId>org.springframework</groupId>
			<artifactId>spring-jdbc</artifactId>
			<version>${spring.version}</version>
		</dependency>
		<dependency>
			<groupId>org.springframework</groupId>
			<artifactId>spring-test</artifactId>
			<version>${spring.version}</version>
			<scope>test</scope>
		</dependency>
		<dependency>
      <!-- Spring-MVC Framework -->
			<groupId>org.springframework</groupId>
			<artifactId>spring-webmvc</artifactId>
			<version>${spring.version}</version>
		</dependency>
		<!-- Servlet API -->
		<dependency>
			<groupId>javax.servlet</groupId>
			<artifactId>javax.servlet-api</artifactId>
			<version>${servlet.version}</version>
		</dependency>
		<!-- MySQL database driver -->
		<dependency>
			<groupId>mysql</groupId>
			<artifactId>mysql-connector-java</artifactId>
			<version>${mysql.connector.version}</version>
		</dependency>
		<!-- Junit -->
		<dependency>
			<groupId>junit</groupId>
			<artifactId>junit</artifactId>
			<version>${junit.version}</version>
			<scope>test</scope>
		</dependency>
	</dependencies>
  
  **Step-3** Inside webapp/WEB-INF/jsp/
