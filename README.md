Movie Information validation
  This repository hold the test cases for two different website i.e. Wikipedia and IMDB these two website are the sources to get the details of movies Pusha: The Rise
  The 2 main files that you will see across these tests are
  1.Wiki_Pushpa_The_Rise 
  2.IMDB Pushpa the rise
  We are building the solution that extract the details of Movie Pusha The rise the details like are as follows
  1.Extract the Country
  2.Extract the release date
  
  ## Required Software
  1.JDK 1.8 or later
  2.Eclipse
  3.Selenium
  4.Language -Java
  5.TestNG 
  
  
  ### Step to develop and run the test script
  1.Create the project in Eclipse
  2.After creating the name the project as per your convenience like in this case, we named Selenium as project name
  3.After creating the project create the Package for classes and Package name is TestNG in this case
  4.so after creating the add jar file for selenium and TestNG as it is required to write the cases for movie data validation
  5.Create the class for test script in this we create two class as mention in the above
  6.So we divide our test script in three section
   i>@BeforeMethod-In this we are launching our browser and website.
   ii>@Test-in this method we are extract the move data which is required
   iii>@AfterMethod-this method is for quoting the browser
   
7.The above test script section are applicable for the both test script as 
8.so to run the test case click on the right side of test script you will see the option Run As-TestNG test
9.so in way we execute the test script and extract the data from the given website as we see the result in the TestNG folder test output 
10. So in the Test output folder there are two reports TestNG_repot.xml and emailable report.
