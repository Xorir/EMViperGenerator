# EMViperGenerator
Project creates folders and files for VIPER

*****

1) Download or clone the project
2) Go to EMViperViewController uncomment line 18
3) Pass module name, project name in which the module is going to be used and compy right holder name into the function
          generator.createModule(moduleName: "naku", projectName: "zz", CopyRightHolder: "dd")
4) Run the project and wait for the folder to pop up.

OR

1) Download or clone the project
2) Create a new Cocoa App project(not cocoa touch)
3) Open downloaded EMViperGenerator folder and drag & drop EMViper.framework to your project
4) YourProject > TARGETS > Embedded Binaries > + EMViper.framework 
5) YourProject > TARGETS > YourProject > Capabilities > App Sandbox ON > choose User Selected File Read/Write
6) ViewController in your project > import EMViper > ViewDidLoad()
  add these lines: 
          let generator = EMViper()
          Pass module name, project name in which the module is going to be used and compy right holder name into the function
          generator.createModule(moduleName: "naku", projectName: "zz", CopyRightHolder: "dd")
7) Run the project and wait for the folder to pop up.          
          
          
