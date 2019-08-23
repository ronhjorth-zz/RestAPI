
<style>
        h1 {
            color:Steelblue;
        }
        h2 {
            color:DeepSkyBlue
        }
        h3{
            color:lightSkyBlue
        }
        Powershell{
            color:green
        }
</style>

# RestFull API 
August 2019 (version .01)

Welcome to the August 2019 release of RestFull API. The API will adhear to the REST constaints, the Richardson Maturity Model. 

Endpoints:
1. /querySchema allows user to query the base schema so they can see what's available to query.
2. /saveQuery allows use to save a query based on clientID and queryName
3. /executeQuery allows the user to execute a saved query based on clientId and queryName
4. /listQueries returns a list of queries available saved by the client by clientId. List active, list all, list deprecated) 
5. /updateQuery ClientID, QueryName
6. /deprecateQuery marks the query as not able to execute. 
8. 

Some of the key highlights include: 
- Fluent Validation - in order to validate the incoming data request and return errors to the requesting client.

Tools:
.Net Core 2.0




## Sections
- [Defi Solutions Notes](#defi-solutions-notes)
    - [Sections](#sections)
    - [Summary of the System](#summary-of-the-system)
    - [General Information](#general-information)
    - [Developer Onboarding](#developer-onboarding)
    - [Application and Code Setup](#Application-and-Code-Setup)
    - [Build Notes](#build-notes)
    - [Databases](#Databases)
    - [Database Migrations](#Database-Migration)
    - [Links](#links)
    - [Images](#images)
    - [Code](#code)
    - [Tables](#tables)
    - [Custom HTML](#custom-html)
    - [Custom CSS](#custom-css)
    - [Additional Resources](#additional-resources)

---