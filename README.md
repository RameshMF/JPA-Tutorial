# JPA-Tutorial - Guide to Java Persistence API


<div dir="ltr" style="text-align: left;" trbidi="on">

<div class="font-family-page">
The Java Persistence API (JPA) is the Java standard for mapping Java objects to a relational database. Mapping Java objects to database tables and vice versa is called Object-relational mapping (ORM). The Java Persistence API (JPA) is one possible approach to ORM. Via JPA the developer can map, store, update and retrieve data from relational databases to Java objects and vice versa. JPA can be used in Java-EE and Java-SE applications.<br>
<br>
JPA is a specification and several implementations are available. Popular implementations are Hibernate, EclipseLink and Apache OpenJPA.<br>
<br>
In this tutorial, we will learn JPA in depth with Hibernate as Implementation.<br>
<ul style="text-align: left;">
<li><a href="http://www.javaguides.net/2018/12/jpa-entity-class-basics.html" target="_blank">JPA Entity Class Basics</a>&nbsp;- Check out how to create JPA entity, what are rules to create JPA entity and what are features JPA Entity provides like cascading, lazy, relationships, inheritance etc.</li>
</ul>
<ul style="text-align: left;">
<li><a href="http://www.javaguides.net/2018/12/jpa-architecture.html" target="_blank">JPA Architecture</a>&nbsp;-&nbsp;In this article, we will discuss the architecture(core classes and interfaces of Java Persistence API) of the JPA specification.</li>
</ul>
<ul style="text-align: left;">
<li><a href="http://www.javaguides.net/2018/12/jpa-obtaining-jpa-database-connection.html" target="_blank">JPA - Obtaining a JPA Database Connection</a>&nbsp;-&nbsp;A connection to a database is represented by an EntityManager instance, which also provides functionality for performing operations on a database.</li>
</ul>
<ul style="text-align: left;">
<li><a href="http://www.javaguides.net/2018/11/jpa-with-hibernate-5-bootstrapping-example.html" target="_blank">JPA 2 with Hibernate 5 Bootstrapping Example</a>&nbsp;-&nbsp;The Java Persistence API (a.k.a. JPA) is a Java specification for managing, persisting and accessing data between objects and relational database. Hibernate is an ORM (Object Relational Mapping) tool which implements JPA specification.</li>
</ul>
<ul style="text-align: left;">
<li><a href="http://www.javaguides.net/2018/11/all-jpa-annotations-mapping-annotations.html" target="_blank">All JPA Annotations: Mapping Annotations</a>&nbsp;-&nbsp;This article provides a quick overview of all JPA mapping annotations quick reference or summary.</li>
</ul>
<ul style="text-align: left;">
<li><a href="http://www.javaguides.net/2018/11/guide-to-jpa-and-hibernate-cascade-types.html" target="_blank">Guide to JPA and Hibernate Cascade Types</a>&nbsp;- Learn various cascade types JPA supports with examples.</li>
</ul>
<h2 style="text-align: left;">
Domain Model</h2>
<ul style="text-align: left;">
<li><span style="background-color: white; color: #24292e; font-family: inherit; font-size: 16px;"><a href="http://www.javaguides.net/2018/11/guide-to-jpa-and-hibernate-cascade-types.html" target="_blank">Guide to JPA and Hibernate Cascade Types</a>&nbsp;- J</span><span style="background-color: white; color: #24292e; font-family: inherit; font-size: 16px;">PA allows you to propagate the state transition from a parent entity to a child. This article describes all cascade types with an example.</span></li>
</ul>
<ul style="text-align: left;">
<li><span style="background-color: white; color: #24292e; font-family: inherit; font-size: 16px;"><a href="http://www.javaguides.net/2018/12/hibernatejpa-primary-key-generation-stratergies.html" target="_blank">Hibernate/JPA - Primary Key Generation Strategies</a>&nbsp;- Let's discuss&nbsp;</span><span style="background-color: white; color: #24292e; font-family: inherit; font-size: 16px;">4 different primary key generation strategies which generate the primary key values programmatically or use database features, like auto-incremented columns or sequences.</span></li>
</ul>
<ul style="text-align: left;">
<li><a href="http://www.javaguides.net/2018/11/hibernate-5-enum-type-mapping-example.html">Hibernate 5 - Enum Type Mapping Example</a>&nbsp;- In this article, we will show you how a Java enum type is persisted into a database.</li>
</ul>
<ul style="text-align: left;">
<li><a href="http://www.javaguides.net/2018/11/hibernate-component-mapping-using-embeddable-embedded-annotation.html" target="_blank">Hibernate Component Mapping Using @Embeddable and @Embedded Annotation</a>&nbsp;-&nbsp;<span style="background-color: white; color: #24292e; font-size: 16px;">With Hibernate we can use the&nbsp;</span><span style="background-color: rgba(27 , 31 , 35 , 0.05); color: #d73a49; font-family: &quot;consolas&quot; , &quot;liberation mono&quot; , &quot;courier&quot; , monospace; font-size: 14.4px; padding: 0.2em 0.4em;">@Embeddable</span><span style="background-color: white; color: #24292e; font-size: 16px;">&nbsp;annotation to mark a class to be eligible as an embeddable class.</span></li>
</ul>
<h2 style="text-align: left;">
<span style="color: #24292e;">JPA Operations</span></h2>
<div>
<ul>
<li><a href="http://www.javaguides.net/2018/12/different-ways-to-store-jpa-entity.html" target="_blank">Different Ways to Store JPA Entity Objects into a Database</a></li>
</ul>
<ul>
<li><a href="http://www.javaguides.net/2018/12/different-ways-to-retrieve-jpa-entity-objects-from-database.html" target="_blank">Different Ways to Retrieve JPA Entity Objects from Database</a></li>
</ul>
<ul>
<li><a href="http://www.javaguides.net/2018/12/different-ways-to-delete-jpa-entity-objects-from-database.html" target="_blank">Different Ways to Delete JPA Entity Objects from Database</a>&nbsp;</li>
</ul>
<div style="text-align: left;">
</div>
<ul>
<li><a href="http://www.javaguides.net/2018/12/different-ways-to-update-jpa-entity-objects-into-database.html" target="_blank">Different Ways to Update JPA Entity Objects into a Database</a>&nbsp;</li>
</ul>
<ul>
<li><a href="http://www.javaguides.net/2018/12/jpa-crud-example.html" target="_blank">JPA CRUD Example</a></li>
</ul>
</div>
<h2 style="text-align: left;">
&nbsp;JPA Core Interfaces</h2>
<div style="text-align: left;">
</div>
<ul style="text-align: left;">
<li><a href="http://www.javaguides.net/2018/12/jpa-entitytransaction-interface-with-example.html" target="_blank">JPA EntityTransaction Interface with Example</a></li>
</ul>
<ul style="text-align: left;">
<li><a href="http://www.javaguides.net/2018/12/jpa-entitymanagerfactory-interface-with-example.html" target="_blank">JPA EntityManagerFactory Interface with Example</a></li>
</ul>
<ul style="text-align: left;">
<li><a href="http://www.javaguides.net/2018/12/jpa-entitytransaction-interface-with-example.html" target="_blank">JPA EntityTransaction Interface with Example</a></li>
</ul>
<h2 style="text-align: left;">
Inheritance Mapping</h2>
<div>
<div style="text-align: left;">
<ul style="text-align: left;">
<li><a href="http://www.javaguides.net/2018/11/hibernate-5-inheritance-mapping.html" target="_blank">Hibernate/JPA - Inheritance Mapping</a>&nbsp;- In this article, we will learn 4 inheritance<span style="background-color: white; font-family: , &quot;blinkmacsystemfont&quot; , &quot;segoe ui&quot; , &quot;helvetica&quot; , &quot;arial&quot; , sans-serif , &quot;apple color emoji&quot; , &quot;segoe ui emoji&quot; , &quot;segoe ui symbol&quot;; font-size: 16px;">&nbsp;strategies with examples.</span></li>
</ul>
<ul style="text-align: left;">
<li><span style="background-color: white; font-family: , &quot;blinkmacsystemfont&quot; , &quot;segoe ui&quot; , &quot;helvetica&quot; , &quot;arial&quot; , sans-serif , &quot;apple color emoji&quot; , &quot;segoe ui emoji&quot; , &quot;segoe ui symbol&quot;; font-size: 16px;"><a href="http://www.javaguides.net/2018/11/hibernate-jpa-mappedsuperclass-inheritance-example.html" target="_blank">Hibernate/JPA MappedSuperclass Inheritance Example</a>&nbsp;-&nbsp;</span><span style="background-color: white; color: #24292e; font-family: , &quot;blinkmacsystemfont&quot; , &quot;segoe ui&quot; , &quot;helvetica&quot; , &quot;arial&quot; , sans-serif , &quot;apple color emoji&quot; , &quot;segoe ui emoji&quot; , &quot;segoe ui symbol&quot;; font-size: 16px;">The JPA standard specification defines the&nbsp;</span><a href="https://docs.oracle.com/javaee/7/api/javax/persistence/MappedSuperclass.html" style="color: #3d85c6; font-size: 16px;" target="_blank">@MappedSuperclass</a><span style="background-color: white; color: #24292e; font-family: , &quot;blinkmacsystemfont&quot; , &quot;segoe ui&quot; , &quot;helvetica&quot; , &quot;arial&quot; , sans-serif , &quot;apple color emoji&quot; , &quot;segoe ui emoji&quot; , &quot;segoe ui symbol&quot;; font-size: 16px;">&nbsp;annotation to allow an entity to inherit properties from a base class.</span></li>
</ul>
<div style="text-align: left;">
</div>
<ul style="text-align: left;">
<li><span style="background-color: white; color: #24292e; font-family: , &quot;blinkmacsystemfont&quot; , &quot;segoe ui&quot; , &quot;helvetica&quot; , &quot;arial&quot; , sans-serif , &quot;apple color emoji&quot; , &quot;segoe ui emoji&quot; , &quot;segoe ui symbol&quot;; font-size: 16px;"><a href="http://www.javaguides.net/2018/11/hibernatejpa-single-table-inheritance.html" target="_blank">Hibernate/JPA Single Table Inheritance Example</a>&nbsp;-&nbsp;</span><span style="background-color: white; color: #24292e; font-family: , &quot;blinkmacsystemfont&quot; , &quot;segoe ui&quot; , &quot;helvetica&quot; , &quot;arial&quot; , sans-serif , &quot;apple color emoji&quot; , &quot;segoe ui emoji&quot; , &quot;segoe ui symbol&quot;; font-size: 16px;">&nbsp;</span><span style="background-color: white; color: #24292e; font-family: , &quot;blinkmacsystemfont&quot; , &quot;segoe ui&quot; , &quot;helvetica&quot; , &quot;arial&quot; , sans-serif , &quot;apple color emoji&quot; , &quot;segoe ui emoji&quot; , &quot;segoe ui symbol&quot;; font-size: 16px;">In this article, we will discuss The single table strategy which maps all entities of the inheritance structure to the same database table.</span></li>
</ul>
<ul style="text-align: left;">
<li><span style="background-color: white; color: #24292e; font-family: , &quot;blinkmacsystemfont&quot; , &quot;segoe ui&quot; , &quot;helvetica&quot; , &quot;arial&quot; , sans-serif , &quot;apple color emoji&quot; , &quot;segoe ui emoji&quot; , &quot;segoe ui symbol&quot;; font-size: 16px;"><a href="http://www.javaguides.net/2018/11/hibernate-jpa-joined-table-inheritance-example.html" target="_blank">Hibernate JPA Joined Table Inheritance Example</a>&nbsp;-&nbsp;</span><span style="background-color: white; color: #24292e; font-family: , &quot;blinkmacsystemfont&quot; , &quot;segoe ui&quot; , &quot;helvetica&quot; , &quot;arial&quot; , sans-serif , &quot;apple color emoji&quot; , &quot;segoe ui emoji&quot; , &quot;segoe ui symbol&quot;; font-size: 16px;">In this article, we will discuss The Joined table strategy or table-per-subclass mapping strategy.</span></li>
</ul>
<ul style="text-align: left;">
<li><span style="background-color: white; color: #24292e; font-family: , &quot;blinkmacsystemfont&quot; , &quot;segoe ui&quot; , &quot;helvetica&quot; , &quot;arial&quot; , sans-serif , &quot;apple color emoji&quot; , &quot;segoe ui emoji&quot; , &quot;segoe ui symbol&quot;; font-size: 16px;"><a href="http://www.javaguides.net/2018/11/hibernatejpa-table-per-class-inheritance-example.html" target="_blank">Hibernate/JPA Table Per Class Inheritance Example</a>&nbsp;-&nbsp;</span><span style="background-color: white; color: #24292e; font-family: , &quot;blinkmacsystemfont&quot; , &quot;segoe ui&quot; , &quot;helvetica&quot; , &quot;arial&quot; , sans-serif , &quot;apple color emoji&quot; , &quot;segoe ui emoji&quot; , &quot;segoe ui symbol&quot;; font-size: 16px;">In this article, we’ll look into Hibernate/JPA table per class inheritance.</span></li>
</ul>
</div>
</div>
</div>
</div>
