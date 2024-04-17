This script provides a simple and effective interface for interacting with the MySQL database using the PHP language. It can be used to perform basic operations such as SELECT and INSERT, to prevent any SQL injection exploits


#use 
  # INSERT
  $s->insert(array('passwd' => 'XQ"W', 'id'=> 1, 'name' => 'Ghaith'), "test");
  
  # Select With Conditions
  $s->select(["id", "name"], "test", array('id'=> 1, 'name' => 'Ghaith', 'passwd' => 'gh'));
  # Select WithOut Conditions
  $s->select(["id", "name"], "test");
