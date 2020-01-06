// Working on table "demo" that has columns "id", "name" and "hint"

// Select everything from the table "demo"
SELECT * FROM demo;

// Insert a new record into the data table
INSERT INTO demo (id, name, hint) VALUES (18, "James", "Guitar");

// Delete a value if it has the name james
DELETE FROM demo WHERE name = "James";

// Update a value 
UPDATE demo SET id = 18 WHERE name = "Atil";
