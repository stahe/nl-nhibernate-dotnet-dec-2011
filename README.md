# Inleiding tot het NHibernate-framework voor het .NET-platform

[Inleiding tot het NHibernate-framework voor het .NET-platform (2011)](https://stahe.github.io/nl-nhibernate-dotnet-dec-2011/)

Deze repository hoort bij een inleidende cursus over **NHibernate**, dat wordt gepresenteerd als het .NET-equivalent van het Java-framework **Hibernate**. Het document biedt een beknopt overzicht van het gebruik van een **ORM** (*Object Relational Mapper*) in het .NET-ecosysteem.

## Overzicht

Een ORM is een verzameling bibliotheken waarmee een applicatie die gebruikmaakt van een database deze kan bewerken **zonder expliciet SQL-query’s te schrijven** en **zonder afhankelijk te zijn van de specifieke kenmerken van het gebruikte DBMS**.

Dit document vormt een **beknopte inleiding** tot NHibernate. Voor een meer diepgaande studie beveelt het document het volgende boek aan:

- **NHibernate in Action**
- **Auteur**: Pierre-Henri Kuaté
- **Uitgever**: Manning
- **ISBN-13**: 978-1932394924

## Niveau en vereisten

Op een schaal van **beginner / gemiddeld / gevorderd** bevindt dit document zich op **gemiddeld** niveau.

Om dit document te kunnen begrijpen, zijn er verschillende vereisten, waaronder:

1. **C# 2008**  
   *Kennis van de programmeertaal C# versie 3.0 met het .NET 3.5-framework*

2. **Spring IoC voor .NET**  
   Inleiding tot de basisprincipes van **Inversion of Control (IoC)** en **afhankelijkheidsinjectie (Dependency Injection)** met **Spring.NET**

Aan het begin van sommige paragrafen bevat het document ook leestips die verwijzen naar deze vereiste voorkennis.

## Gebruikte tools

De casestudy is gebaseerd op tools die gratis beschikbaar zijn op het internet, in de versies die in **december 2011** werden vermeld:

- **NHibernate 3.2**
- **Spring.NET 1.3.2**  
  Hier gebruikt voor de bibliotheken die het gebruik van NHibernate vergemakkelijken
- **log4net 1.2.10**  
  Logboekframework dat door NHibernate wordt gebruikt
- **NUnit 2.5**  
  Framework voor unit-tests, het .NET-equivalent van JUnit
- **ADO.NET-driver 6.4.4 voor MySQL 5**

## Doel van de cursus

Deze cursus heeft tot doel de basisbeginselen van **NHibernate** in een .NET-context te introduceren, door te laten zien hoe de toegang tot gegevens kan worden vereenvoudigd dankzij een objectgeoriënteerde aanpak, waarbij gebruik wordt gemaakt van aanvullende tools voor configuratie, logboekregistratie en testen.

