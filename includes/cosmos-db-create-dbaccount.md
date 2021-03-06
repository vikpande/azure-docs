1. In a new browser window, sign in to the [Azure portal](https://portal.azure.com/).
2. Click **New** > **Databases** > **Azure Cosmos DB**.
   
   ![The Azure portal Databases pane](./media/cosmos-db-create-dbaccount/create-nosql-db-databases-json-tutorial-1.png)

3. In the **New account** page, enter the settings for the new Azure Cosmos DB account. 
 
    Setting|Suggested value|Description
    ---|---|---
    ID|*Enter a unique name*|Enter a unique name to identify this Azure Cosmos DB account. Because *documents.azure.com* is appended to the ID that you provide to create your URI, use a unique but identifiable ID.<br><br>The ID can contain only lowercase letters, numbers, and the hyphen (-) character, and it must contain 3 to 50 characters.
    API|SQL (document)|The API determines the type of account to create. Azure Cosmos DB provides four APIs to suits the needs of your application:SQL (document), MongoDB (document), Table (key-value), and Gremlin (graph) each which currently require a separate account. <br><br>Select **SQL (document)** because in this quickstart you are creating a document database that is queryable using SQL syntax and accessible with the DocumentDB API.<br><br>[Learn more about the DocumentDB API](../articles/cosmos-db/documentdb-introduction.md)|
    Subscription|*Your subscription*|Select Azure subscription that you want to use for this Azure Cosmos DB account. 
    Resource Group|*Enter the same unique name as provided above in ID*|Enter a new resource-group name for your account. For simplicity, you can use the same name as your ID. 
    Location|*Select the region closest to your users*|Select geographic location in which to host your Azure Cosmos DB account. Use the location that's closest to your users to give them the fastest access to the data.
    Enable geo-redundancy| Leave blank | This creates a replicated version of your database in a second (paired) region. Leave this blank.  
    Pin to dashboard | Select | Select this box so that your new database account is added to your portal dashboard for easy access.

    Then click **Create**.

    ![The new account blade for Azure Cosmos DB](./media/cosmos-db-create-dbaccount/create-nosql-db-databases-json-tutorial-2.png)

4. The account creation takes a few minutes. During account creation the portal displays the **Deploying Azure Cosmos DB** tile.

    ![The Azure portal Notifications pane](./media/cosmos-db-create-dbaccount/deploying-cosmos-db.png)

    Once the account is created, the **Congratulations! Your Azure Cosmos DB account was created** page is displayed. 

