# cucumberpom.xml

<project xmlns="http://maven.apache.org/POM/4.0.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 https://maven.apache.org/xsd/maven-4.0.0.xsd">
	<modelVersion>4.0.0</modelVersion>
	<groupId>cucumber</groupId>
	<artifactId>cucumber</artifactId>
	<version>0.0.1-SNAPSHOT</version>
	<!-- https://mvnrepository.com/artifact/io.cucumber/cucumber-junit -->
	<dependencies>
		<dependency>
			<groupId>io.cucumber</groupId>
			<artifactId>cucumber-junit</artifactId>
			<version>7.3.4</version>
			<scope>test</scope>
		</dependency>
		<dependency>
			<groupId>info.cukes</groupId>
			<artifactId>cucumber-core</artifactId>
			<version>1.2.5</version>
		</dependency>
		<dependency>
			<groupId>info.cukes</groupId>
			<artifactId>cucumber-java</artifactId>
			<version>1.2.5</version>
			<scope>test</scope>
		</dependency>
		<dependency>
			<groupId>info.cukes</groupId>
			<artifactId>cucumber-jvm-deps</artifactId>
			<version>1.0.5</version>
			<scope>provided</scope>
		</dependency>
		<dependency>
			<groupId>net.masterthought</groupId>
			<artifactId>cucumber-reporting</artifactId>
			<version>3.12.0</version>
		</dependency>

		<!-- GHERKIN PLUGIN -->
		<dependency>
			<groupId>info.cukes</groupId>
			<artifactId>gherkin</artifactId>
			<version>2.12.2</version>
			<scope>test</scope>
		</dependency>

		<!-- MOCKITO PLUGIN -->
		<dependency>
			<groupId>org.mockito</groupId>
			<artifactId>mockito-all</artifactId>
			<version>1.10.19</version>
			<scope>test</scope>
		</dependency>

		<!-- COBERTURA PLUGIN -->
		<dependency>
			<groupId>net.sourceforge.cobertura</groupId>
			<artifactId>cobertura</artifactId>
			<version>2.1.1</version>
			<scope>test</scope>
			<exclusions>
				<exclusion>
					<artifactId>tools</artifactId>
					<groupId>com.sun</groupId>
				</exclusion>
			</exclusions>
		</dependency>

		<!-- ALLURE PLUGIN -->
		<dependency>
			<groupId>ru.yandex.qatools.allure</groupId>
			<artifactId>allure-cucumber-jvm-adaptor</artifactId>
			<version>1.6.4</version>
		</dependency>


		<dependency>
			<groupId>info.cukes</groupId>
			<artifactId>cucumber-java</artifactId>
			<version>1.1.5</version>
			<scope>test</scope>
		</dependency>

		<dependency>
			<groupId>info.cukes</groupId>
			<artifactId>cucumber-jvm</artifactId>
			<version>1.1.5</version>
			<type>pom</type>
		</dependency>

		<dependency>
			<groupId>info.cukes</groupId>
			<artifactId>cucumber-junit</artifactId>
			<version>1.1.5</version>
			<scope>test</scope>
		</dependency>
		<dependency>
			<groupId>info.cukes</groupId>
			<artifactId>cucumber-jvm-deps</artifactId>
			<version>1.0.5</version>
		</dependency>
		<dependency>
			<groupId>net.masterthought</groupId>
			<artifactId>cucumber-reporting</artifactId>
			<version>1.0.0</version>
		</dependency>
		<dependency>
			<groupId>info.cukes</groupId>
			<artifactId>gherkin</artifactId>
			<version>2.12.2</version>
		</dependency>
		<dependency>
			<groupId>org.mockito</groupId>
			<artifactId>mockito-all</artifactId>
			<version>2.0.2-beta</version>
		</dependency>
		<dependency>
			<groupId>junit</groupId>
			<artifactId>junit</artifactId>
			<version>3.8.1</version>
			<scope>test</scope>
		</dependency>


	</dependencies>
</project>
