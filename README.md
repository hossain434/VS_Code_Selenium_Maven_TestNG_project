# VS_Code_Selenium_Maven_TestNG_project

Setting Up Selenium Using Java On Visual Studio Code

1. In VS Code, install plugin for Java extension pack.

2. Install plugin for openjdk (if required).

3. Install Maven plugin.

4. On VS Code ctrl+shift+P (command pallete), Type: Maven: Create new project, select archetype: quickstat (simplest one). Sample maven project will create with junit installed.

5. Add dependency testng, selenium-java, selenium-chromedriver in pom.xml.

6. Make sure pom.xml in current project directory.

7. Build command: mvn package, mvn clean, mvn install. 
