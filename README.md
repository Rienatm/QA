# QA
File 1: Rienat Apache JMeter5.5.jmx for Apache JMeter 5.5. (stress test, load test, response speed)
File 2: Rienat.postman_cycle.json for Postman
   1.Create a user.
   2.Add 10 cars for the user.
   3.Create another user.
   4.Add 10 cars for another user.
   5.Ensure the model and mileage of each car are correct. There only one pm.test in collection! (cycle js)
File 3: Rienat.postman_test.json for Postman
   1.Create a user. Verify that the user is created with the specified parameters
   2.Create an auto user. Check what has been created with the specified parameters.
   3.We are creating an eccpens for cars. We are checking to see if there are any changes.
   4.Retracting. Check that the auto and experience parameters have not changed.
   5.Change user’s email. Check that the new settings are applied
   6.Check that auto and experience parameters did not fail after changing the email.
   7.We edit the parameters by increasing the amount of fuel and money. Check that the parameters are applied.
   8.Delete the user.
