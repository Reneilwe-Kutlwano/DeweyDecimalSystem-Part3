# DeweyDecimalSystem-Part3
#### =============TABLE OF CONTENTS===============
1. Overview.
2. Features of the project.
3. Development dependencies.
4. Technology + software required.
5. Running of the project.
6. List of files in the directory.
7. Troubleshooting.
8. Contributors and sources.

#### ======================OVERVIEW=========================
This is an interactive application that allows librarians to be able to uniquley replace books, identify areas and find call numbers online through fun and innovative ways that essentially remove the tedious aspects of replacing and locating books in a library. This application encompasses a unique gamified way to sort books based on their respective call numbers. In a nutshell librarians will be able to drag and drop relevant call numbers and arrange them numerically then alphabetically, match call numbers to descriptions and vice versa as well as identify which lower level categories belong to which higher and middle and lower level call numbers and descriptions. Once they are satisfied with their choice they will can click on the option they believe is the answer and obtain points. This application creates healthy competion amongst the librarians and essentially takes away from the boring aspects of their job.

The motivation behind this application was to create something a six year old will enjoy. We as humans tend to fall into the trap of living a life of routine and constant work with not rewards. This application aims to solve that, it provides a way to bring back the fun and interesting elements of being a librarian.

#### =================FEATURES OF THE PROJECT.===================
This project includes the following:
1. A home page/ landing page in which the users will click on the task they would like to do today.
2. All three buttons have now been enabled
3. A replacing books page in which the users will generate random numbers and have the ability to drag and drop them from one box to the other.
4. Instructions on how the game works in all three tasks.
5. An identifying areas page in which the users will match call numbers to descriptions and vice versa from column A to column B.
6. A timer (gamification feature) to bring about competion amongst the users on who sorts the fastest before the timer ticks.
7. Drag and drop validation in the event the user does not drag or drop accordingly.
8. Empty fields validation, to make sure users are selecting options in the combo boxes and not submitting empty values.
9.Toast notifications to demonstrate to the user if they have arranged the call numbers correctly.
10.Message boxes to demonstrate to the users if they have successfully matched the columns to move onto the next task.
11. A finding call numbers page in which users will be presented with a third level description in which they need to match which top level, middle and lower level call number and description it belongs to.
12. A points gamification feature. On correct selection the user will earn 10 points and -5 points on incorrect selection with a given high score.
13.Restart button to allow the user to restart the game.
14.End button to close the page and return you to the home screen.

#### =================DEVELOPMENT DEPENDENCIES.================
1. Visual studio 2019/2022
2. Toast notifications for WPF 2.5.1
3. ToastNotifications.Messages for WPF 2.5.1
4. Visual studio WPF(.NET Framework) Core 5.0

#### ===========TECHNOLOGY + SOFTWARE REQUIRED==========
1. A laptop that supports 
   windows 8, 8.1, 
   windows XP, 
   windows Vista SP 2, 
   windows 7 SPI
   windows10 and microsoft with atleast 4GB of RAM space, x86 or x84 CPU and HDD space of up to 1.5 GB available.
2. Not supported on: 
   Linux 
   MS-DOS (IBM PC DOS) 
   Windows 3.1 
   Windows NT 3.51 
   Windows 9x 
   Windows NT 4.0.
3. Microsoft visual studio 2019 version 16.9.4./ Microsoft visual studio 2022 version 17.3.4
4. .NET Framework 5.0
5. .NET Core 3.1
6. .NET 5.0
7. WPF on .NET Core 5.0

#### ============RUNNING OF THE PROJECT (INSTALLATION AND OPERATION)===================
1. Download the zipped folder(ST10122290.Prog 7312. Final Poe.zip)
2. In the file explorer unzip the zipped file by extracting it.
3. Open the unzipped file.
4. Click the Library system ST10122290 file to open it.
5. Open the folder that says Library system ST10122290.Sln.
6. Visual studio 2022 will open now.
7. Once the application is opened click the green "start" button to run the application.
8. The programme will start with the home page in which the user will select the task they want to start with.
9. In this instance the user will select the finding call numbers button.
10. Once this button is pressed you will be redirected to the finding call numberes page.
11. On the finding call numbers page the user will be presented with a question and 4 options to choose from.
12. The user would be required to select an option that best fits the question, essentially they would need to figure out which top level, middle and lower level call number and description does the question belong to.
13. On an option selection the user will be presented with a message on whether it is correct and incorrect with points allocated for each.
14. In the event that the user decides that they wish to generate a new question, there is a restart button that will restart the game.
15. The game will continue this way up until the user is not successful or wishes to end the game.
16. If the user wishes to end the game, there is an end button that will close the application and return you to the main screen.


#### ============LIST OF FILES IN THE DIRECTORY===================
1. When opening the zip file, open the Library system.ST10122290
2. Once opened click on the Library system.ST10122290 sln file to run the project.

--In the project there is:
1. App config 
2. App
3. App.xaml.cs with Toast theme file added (<ResourceDictionary>
                                            <ResourceDictionary.MergedDictionaries>
                                            <ResourceDictionary Source="pack://application:,,,/ToastNotifications.Messages;component/Themes/Default.xaml" />
                                            </ResourceDictionary.MergedDictionaries>
                                            </ResourceDictionary>)
4. MainWindow.xaml.cs
5. MainWindow.xaml
6. replacingBooks.xaml.cs
7. replacingBooks.xaml
8. generateClass.xaml.cs
9. identifyingAreas.xaml.cs
10.identifyingAreas.xaml
11.subsitituteIdentifyingAreas.xaml.cs
12.subsitituteIdentifyingAreas.xaml
13.findingCallNumbersTree.cs
14.findingCallNumbers.xaml
14.findingCallNumbers.xaml.cs

#### ============COPYRIGHT AND LICENSING===================
1. .NET Framework generate licensce.licx.file
2. DLL references
3. NuGet packages

#### ============TROUBLESHOOTING===================
1. In the event the application crashes or stops working, make sure to restart Visual studio completely.
2. Close Visual studio and reload it, the application will reload and start working.
3. In the event the application keeps stopping, make sure you have met the mimimum dependency requirements of the application prior to running.

#### ============CONTRIBUTORS AND SOURCES===================
1. Reneilwe Motlhabi - rkmotlhabi@gmail.com - 064 630 8435
2. Jamro.K. 2018. C# Data structures and algotihms. Birmingham, Packt publishing.
3. Lilz. 2019. Interactive toast notification. 19 December 2019. [Lilz]. Available at: https://www.youtube.com/watch?v=z9GuTERyH3A
[Accessed 18 September 2022].
4. Rayhaan Nakooda. 2021. Github https://github.com/RayhaanNakooda Accessed 23 October 2022.
5. Delftstack. 2021. Get dictionary key by value in C#. Available at: https://www.delftstack.com/howto/csharp/get-dictionary-key-by-value-in-csharp/
6. Luke Mauve. 2021. Github https://github.com/LukeMauve-Lawrence Accessed 17 November 2022.
