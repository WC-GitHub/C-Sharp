//add reference for console application
using System;
using System.Data.SqlClient;
using System.Configuration;

//form load
String Status = "";
SqlConnection connection = new SqlConnection(ConfigurationManager.ConnectionStrings["connectionString"].ConnectionStrings);
try
{
	connection.Open();
	Status = "C# Connection SQL Server sucessfully.";
}
catch (Exception e)
{
	Status = e.Message;
}
finally
{
	connection.Close();
}
Console.WriteLine(Status);
Console.ReadLine();
