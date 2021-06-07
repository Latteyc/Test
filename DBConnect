import com.mysql.cj.jdbc.MysqlDataSource;
import java.sql.*;
import java.util.logging.Level;
import java.util.logging.Logger;
/**
 *
 * @author latte
 */
public class DBConnect {
  public static void main(String[] args) {
	DBConnect obj_DBConnect = new DBConnect();
	Connection connection = null;
	connection = obj_DBConnect.connect();
	System.out.println(connection);
	}
     public static Connection connect(){
	Connection connection = null;
	try{
		connection = DriverManager.getConnection("jdbc:mysql://databasewebsite:3306/databasename","databaseuser","databasepassword");
	}catch(Exception ex){
System.out.println("There were errors while connecting to db.");
return null;
}
	return connection;
     }}
