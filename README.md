# E-Commerce Back End
![University of Denver Logog](https://d92mrp7hetgfk.cloudfront.net/images/sites/misc/denver-switchup-thumbnail-a/original.png?1560210160)
## Acceptance Criteria
### GIVEN a command-line application that accepts user input
 |When       | Then
 | --------- |--------
 |  I add my database name, MySQL username, and MySQL password to an environment variable file | I am able to connect to a database using Sequelize
 | I enter schema and seed commands | A development database is created and is seeded with test data
 | I enter the command to invoke the application | My server is started and the Sequelize models are synced to the MySQL database
 | I open API GET routes in Insomnia for categories, products, or tags | The data for each of these routes is displayed in a formatted JSON
 | I test API POST, PUT, and DELETE routes in Insomnia | I am able to successfully create, update, and delete data in my database

 ## Grading Requirements

**Note** If a Challenge assignment submission is marked as “0”, it is considered incomplete and will not count towards your graduation requirements. Examples of incomplete submissions include the following:
 * A repository that has no code
 * A repository that includes a unique name but nothing else
 * A repository that includes only a README file but nothing else
 * A repository that only includes starter code

### Deliverables: 10%
 * Your GitHub repository containing your application code.

### Walkthrough Video: 37%
 * A walkthrough video that demonstrates the functionality of the e-commerce back end must be submitted, and a link to the video should be included in your readme file.
 * The walkthrough video must show all of the technical acceptance criteria being met.
 * The walkthrough video must demonstrate how to create the schema from the MySQL shell.
 * The walkthrough video must demonstrate how to seed the database from the command line.
 * The walkthrough video must demonstrate how to start the application’s server.
 * The walkthrough video must demonstrate GET routes for all categories, all products, and all tags being tested in Insomnia.
 * The walkthrough video must demonstrate GET routes for a single category, a single product, and a single tag being tested in Insomnia.
 * The walkthrough video must demonstrate POST, PUT, and DELETE routes for categories, products, and tags being tested in Insomnia.

### Technical Acceptance Criteria: 40%
 * Satisfies all of the preceding acceptance criteria plus the following:
  * Connects to a MySQL database using the [MySQL2](https://www.npmjs.com/package/mysql) and [Sequelize](https://www.npmjs.com/package/sequelize) packages.
  * Stores sensitive data, like a user’s MySQL username, password, and database name, using environment variables through the [dotenv](https://www.npmjs.com/package/dotenv) package.
  * Syncs Sequelize models to a MySQL database on the server start.
  * Includes column definitions for all four models outlined in the Challenge instructions.
  * Includes model associations outlined in the Challenge instructions.

### Repository Quality: 13%
 * Repository has a unique name.
 * Repository follows best practices for file structure and naming conventions.]
 * Repository follows best practices for class/id naming conventions, indentation, quality comments, etc.
 * Repository contains multiple descriptive commit messages.
 * Repository contains a high-quality readme with description and a link to a walkthrough video.

### Repository Link
 * https://github.com/David-Irving/E-CommerceBackEnd

### Preview of Application




https://user-images.githubusercontent.com/99232675/173726454-6471bc07-0f6e-4ce3-b15d-7f8ffcfb8c6b.mov

