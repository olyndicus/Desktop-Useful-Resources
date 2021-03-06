# Java Programming Resources
All useful resource links for Java programming From Java Desktop Basic to Java Enterprise Edition

<h3>IDE - Integrated Development Environment </h3>
IDE for Java :<br/>
1. <a href="http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html" target="_blank">Java Development Kit (JDK) /  Java Runtime Environtment (JRE)</a><br/>
2. <a href="http://www.oracle.com/technetwork/java/javase/downloads/jdk-netbeans-jsp-142931.html" target="_blank">Netbeans 8 IDE bundles</a><br/>
3. <a href="https://eclipse.org/downloads/" target="_blank">Eclipse IDE Repository</a><br/>

<h3>Basic - Tutorial & Components</h3>
1. GUI (Graphical User Interface)<br/>
Ubah tampilan GUI default java "nimbus" ke tampilan "windows".

```Java
try {
    for (javax.swing.UIManager.LookAndFeelInfo info : javax.swing.UIManager.getInstalledLookAndFeels()) {
        if ("Windows".equals(info.getName())) {
            javax.swing.UIManager.setLookAndFeel(info.getClassName());
            break;
        }
    }
}
```

2. Additional Java Info<br/>

<h3>Java Framework</h3>
1. <a href="" target="_blank">Java Hibernate</a><br/>
2. <a href="https://spring.io/" target="_blank">Spring</a><br/>
3. 

<h3>Advanced - Java and the Semantic Web Components (web / desktop)</h3>
1. <a href="https://jena.apache.org/documentation/ontology/" target="_blank">Ontology</a><br/>
2. <a href="https://jena.apache.org/documentation/rdf/index.html" target="_blank">RDF (Resource Description Framework)</a><br/>
3. <a href="https://jena.apache.org/documentation/query/index.html" target="_blank">ARQ - SPARQL RDF Query</a><br/>
4. <a href="https://jena.apache.org/download/" target="_blank">Apache Jena Download</a><br/>
5. 

<h3>Advanced - <a href="https://spring.io/projects/spring-framework" target="_blank">Java Spring Framework</a></h3>
1. <a href="https://spring.io/guides/gs/rest-service/" target="_blank">Spring Web Services</a><br/>
2. <a href="https://spring.io/guides/gs/gradle/" target="_blank">Spring with Gradle</a><br/>
3. <a href="https://spring.io/guides/gs/spring-boot/" target="_blank">Spring Boot</a><br/>
4. <a href="https://spring.io/guides/gs/consuming-rest-jquery/" target="_blank">Consuming Rest with JQuery</a><br/>

Simple example for consuming restful service by using JQuery
```Javascript
function addActivitiesFunction(){
    \$.ajax({
        url		: 'http://172.25.2.149:8080/activities/addactivities',
        type		: 'POST',
        contentType	: 'application/x-www-form-urlencoded',
        data		: getDataAddMasterActivities(),
        success		: function(response) {addMasterActivitiesResult(response)},
        error		: function(e) {onError(e)}
    });
}
```
        
5. <a href="https://spring.io/guides/gs/rest-service-cors/" target="_blank">Defining CORS</a><br/>
