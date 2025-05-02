|Category    |Label             |Value                                                                                                                                             |
|------------|------------------|--------------------------------------------------------------------------------------------------------------------------------------------------|
|Bug ID      |Bud ID Number     |#002                                                                                                                                              |
|            |Reporter's Name   |Torneukari Eyitweremi                                                                                                                             |
|            |Assigned Developer|                                                                                                                                                  |
|            |Submit Date       |4/21/2025                                                                                                                                         |
|Bud Overview|Summary           |The product page is showing showing template binding expressions as {{::product.price|currency:'$'}} instead of showing proper product description|
|            |URL               |https://advantageonlineshopping.com/#/                                                                                                            |
|            |Screenshot        |                                                                                                                                                  |
|Environment |Platform          |Android                                                                                                                                           |
|            |Operating System  |                                                                                                                                                  |
|            |Browser           |Mobile Chrome                                                                                                                                     |
|Bug Details |Steps to Reproduce|1) Login using the link https://advantageonlineshopping.com/#/ 2) Go to product section  3) Click on the products to view                         |
|            |Expected Result   |Product name , price and description should be displayed correctly                                                                                |
|            |Actual Result     |The page show raw angular style template bindings like {{::product.price|currency:'$'}} instead of real values                                    |
|Bug Tracking|Severity          |High                                                                                                                                              |
|            |Priority          |Medium                                                                                                                                            |
