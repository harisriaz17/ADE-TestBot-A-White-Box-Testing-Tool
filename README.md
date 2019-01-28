## ADE-TestBot: A White Box Testing Tool

> NOTE: Due to Git LFS not allowing individual file sizes over 100MB to be uploaded, I have uploaded the entire code as a .zip file. Your first step should be to unzip it.

## Intro
The human dependency on computing technology is increasing exponentially, ranging
from simple house hold chores to safety and mission critical tasks involving domains
like healthcare, transportation and banking. Thus, it is becoming increasingly important
that these softwares running on computers work without any major flaws.

Software testing is used to ensure an error free completion of the tasks performed by a software.

ADE Testbot is a white box testing tool that is capable of performing dead code, exception and assertion testing of a C++ software under
test (SUT). Other unique features of the testing tool include an easy to use graphical user interface (GUI) and its open-source nature.

## Methodology
![Methodology](README-assets/snap-100.png)
## Supported function return types
```
int
bool
double
float
```
## Requirements
- Visual Studio 2017 (https://visualstudio.microsoft.com/downloads/)  
- Qt 5.6 or Qt 5.7 (https://download.qt.io/archive/qt/5.7/5.7.0/)
- Qt Visual Studio tools extension (https://marketplace.visualstudio.com/items?itemName=TheQtCompany.QtVisualStudioTools-19123)

## Instructions 
Run the WhiteBoxTesting.sln file.
- In the “Automated Test Analyzer” window that appears enter the location of your vcvarsall.bat file. Click on the “Browse” button and enter “vcvarsall.bat” in the search box. Double click the first option of the vcvarsall.bat that appears.
- In the second field enter the location of the file that you want to test out. You can click the “Browse” button to search for and select your test file.
- Enter the location of the folder where you would like to save the generated test code. Make sure that the location you have chosen has any files that the test file needs to have included, to avoid any errors. Also it should have two empty files logfile.txt and logfile1.txt where log of assertion-test and exception-test are written.
- Click on the “Next” button after you have entered all the fields.
- A list of functions will appear. You can use the search bar to search the function on which you would like to perform the test. Double click the function of your choice and click the “Next” button.
- Choose the type of test you want to run from the dropdown menu. The choices can be made from the dead code test, where you can make the selection between “Exhaustive” or “Random” test. You can also select the exception test option and enter the step size and the limit for your test. Lastly, you can select the assertion test and enter your own assertion and test it.
- Click the “Run Test” button.
- The command prompt will open and your test will run. Once the test is complete click on the “Check Log” button to check the log of your test.
- You can click on the “New Test” button to run a new test.

## Project Demo (Performing Exception Test on C++ module)
![xx](README-assets/snap-1.png)
## Screen 2
![xx](README-assets/snap-2.png)
## Screen 3
![xx](README-assets/snap-3.png)
## Screen 4
![xx](README-assets/snap-4.png)
## Screen 5
![xx](README-assets/snap-5.png)


