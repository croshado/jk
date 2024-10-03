# jk

To delete the **scrabble** database in MongoDB using the CLI, follow these steps:

1. **Connect to MongoDB:**

   If you're not already connected, you can do so by running:

   ```bash
   mongosh
   ```

2. **Switch to the scrabble database:**

   ```bash
   use scrabble
   ```

3. **Drop the database:**

   You can drop the database using the following command:

   ```bash
   db.dropDatabase()
   ```

This command will delete the **scrabble** database and all its collections and documents.

### Confirming Deletion

To confirm that the database has been deleted, you can run:

```bash
show dbs
```

The **scrabble** database should no longer appear in the list.
