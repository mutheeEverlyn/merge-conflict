--git is a version control system that keeps track of changes in your code
--github is an online platform that helps you store and manage your projects in form of repositories
--merge conflict occurs when you try to merge two branches with the same file but are contradicting in certain piece of code
<!-- merge conflict example-->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>creating a merge conflict and solving it</title>
</head>
<body>
    <h1>merge conflict simulation</h1>
<<<<<<< HEAD
    <p>master  branch merge conflict</p>
=======
    <p>test branch</p>
>>>>>>> test
</body>
</html>
<!-- how to solve -->
--delete line 13,15,16 and 17
--add the changes to the main branch then commit and you have solved the merge conflict