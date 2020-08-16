# CustomModule using GraphQl

# About GraphQl

* GraphQl is an open source server side technology which was developed by facebook to optimize RESTFUL API calls.
* It is an execution engine and a data query language.
* GraphQl structures data in the form of a graph with its powerful query syntax for traversing, retrieving and modifying data.
* The request made by a client to the GraphQl server is called a query.
* GraphQl is a query language for APIs - not a databases.

# REST API vs GraphQl


| Graph Ql | REST API |
| --- | --- |
| Single endpoint| Lots of end point |
| Client decide how data is returned | Server side decide how data is returned |
| Schema based | There is no schema for the data |
| Performance fast | Multiple network calls take up more time|
| Development speed rapid | Development speed slower|
| Operations- Query,Mutations,subscriptions | Operations- CRUD|
| Specific data with a single API calls | Fixed data with multiple API calls |
| Community growing | Community large |

# Module Structure

A GraphQL module’s schema.graphqls file defines how the attributes defined in the module can be used in GraphQL queries and mutations.
The <module_name>/etc/schema.graphqls file:
* Defines the structure of queries and mutations.
* Determines which attributes can be used for input and output in GraphQL queries and mutations. Requests and responses contain separate lists of valid attributes.
* Points to the resolvers that verify and process the input data and response.
* Serves as the source for displaying the schema in a GraphQL browser.
* Defines which objects are cached.
            
# Resolver

*  A resolver performs GraphQL request processing.
* It is responsible for: 
  constructing a query 
  * fetching data
  * performing any calculations 
  * transforming the fetched and calculated data into a GraphQL array format
  * finally, it returns the query results for rendering


# Magento2 Core Module

* BundleGraphQl
* CatalogGraphQl
* CatalogInventoryGraphQl
* CatalogUrlRewriteGraphQl
* CmsGraphQl
* CmsUrlRewriteGraphQl
* ConfigurableProductGraphQl
* CustomerGraphQl
* DownloadableGraphQl
* EavGraphQl
* GroupedProductGraphQl
* QuoteGraphQl
* StoreGraphQl
* SwatchesGraphQl
* TaxGraphQl
* ThemeGraphQl
* UrlRewriteGraphQl
* WeeeGraphQl

# GraphQl Tool

* GraphiQL is an in-browser tool for write and testing GraphQl queries.
* For Google Chrome, ChromeiQL extension is supported, GraphQl Query. Others are Altair GraphQl addon used in both Firefox as well as Chrome.

