# CSE-687-Project-2

Notes regarding this submission:

This project contains not only the files for this project but a TestDriver subproject that builds and holds the TestDriver.dll file. If any changes happen to this project the solution needs to be rebuilt in Visual Studio in order to update the TestDriver.dll file. The project accesses this DLL via a relative path that would most likely need to be updated if any other DLL is used.

The TestDriver subproject uses the ctime function in order to log timestamps. This function usually throws warnings on compile due to the function being deprecated but Visual Studio prevents the solution from building because of this warning. For this subproject in Visual Studio I went to "Configuration Settings" > "C/C++" > "General" and set "SDL Checks" to "No".

For XML parsing, this project uses the tinyxml-2 package. The documentation for this package can be found here: http://www.grinninglizard.com/tinyxml2/
