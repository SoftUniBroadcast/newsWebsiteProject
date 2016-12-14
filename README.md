# newsWebsiteProject
A SoftUni Software Technologies project developed for learning

Project workflow:

1. Added date to Article on creation
2. Created Position Entity with the following functionality
 -> Create, Edit, Delete;
 -> Show author position on Article details view;
 -> Added user position on User/Edit;
 -> When admin deletes a position all users that had this position are set to "Guest" position before it's deletion;
 -> When admin tries to edit or delete "Guest" position he is redirected to position list as "Guest" is the default position and cannot be deleted
3. Added "Our team" page - still work to be done on that view
4. Created "My Articles" view from My profile page, listing all user articles in a table with options to edit/delete. Also when accessing My articles check is made on wether the logged user Id equals the one from the url (the path variable).
5. Created Video Entity with all relations and create functionality. More details to be added in later commits.
