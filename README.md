#**Team City Ant Test Runner**  
  
Allows for integration between TeamCity and ant Robotium instrumentation tests for Android platform. Commands such as run-tests or clean coverage display proper testing results while build is running. 

###**Requirements**  
Unix with Android testing evironment. TeamCity and ruby 1.8 + .  
  
###**Installation**  
In root TCATR directory run 'rake install'.  
  
###**Output**  
You should see the following output.  
cp -f teamCityAnt /usr/local/bin/teamCityAnt  
chmod +x /usr/local/bin/teamCityAnt  
  
May require root permissions.  
  
###**Example use**  
ant clean coverage | teamCityAnt  
  
![Example](https://github.com/curiousminds/teamCityAntTestRunner/raw/master/teamcity_example.png "Example")
