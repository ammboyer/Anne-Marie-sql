Challenge 3\_ todo list stats

CREATE TABLE todo_list (id INTEGER PRIMARY KEY, item TEXT, minutes
INTEGER);

INSERT INTO todo_list VALUES (1, "Wash the dishes", 15);

INSERT INTO todo_list VALUES (2, \"Vacuuming\", 20);

INSERT INTO todo_list VALUES (3, \"Learn some stuff on KA\", 30);

INSERT INTO todo_list VALUES (4, \"Dishes\", 10);

SELECT SUM(minutes) FROM todo_list;
