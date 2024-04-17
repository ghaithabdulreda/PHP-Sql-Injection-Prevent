This script provides a simple and effective interface for interacting with the MySQL database using the PHP language. It can be used to perform basic operations such as SELECT and INSERT, to prevent any SQL injection exploits


#use 

  $s->insert(array('passwd' => 'Passwd123', 'id'=> 1, 'name' => 'Ghaith'), "test");
  
  $s->select(["id", "name"], "test", array('id'=> 1, 'name' => 'Ghaith', 'passwd' => 'Password123@$'));
