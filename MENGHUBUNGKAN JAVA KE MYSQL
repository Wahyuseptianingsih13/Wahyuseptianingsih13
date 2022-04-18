/*

 * To change this license header, choose License Headers in Project Properties.

 * To change this template file, choose Tools | Templates

 * and open the template in the editor.

 */

  import java.sql.*;

/**

 *

 * @author PC

 */

  

public class Koneksi {

      public static void main(String Args[]){

      Koneksi.konek();

      }

  static final String driver = "com.mysql.jdbc.Driver";

  static final String db = "jdbc:mysql://localhost/db_ayu";

  static final String user = "root";

  static final String password = "";

  static Connection conn;

public static void konek(){

    try{

        Class.forName(driver);

        conn = DriverManager.getConnection(db,user,password);

        System.out.println("Koneksi Berhasil");

}

    catch (Exception e){

        System.out.println("Gagal Koneksi");

}

}

}
