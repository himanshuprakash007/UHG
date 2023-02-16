## Installing ActivityAssertUnitTest Package in UiPath Studio

Add this Nuget Package in the UiPath Studio in order to use the "AssertUnitTest" Activity.

Steps to add the Nuget:

1. In the Manage Packages window, in the left panel, right-click any category.

    ![Alt text](images/1.png?raw=True)

2. Select Configure Sources from the context menu. The Package Source Settings window is displayed.

3. Click the Add image alt text button. A new blank feed is added and an error message is displayed because the Name and Source fields are not filled in correctly.

    ![Alt text](images/2.png?raw=True)

4. In the Name field, type the name of the NuGet feed you want to create.

5. In the Source field, type the local drive folder pathway, the shared network folder pathway or the URL of the folder where the Nuget Package(ActivityAssertUnitTest.1.0.0.nupkg) is kept.

    ![Alt text](images/3.png?raw=True)

6. Click Apply. Your configuration is saved.

7. Click OK. The Package Source Settings window closes. Note that the Name is displayed in the Manage Packages window, as a new category.

    ![Alt text](images/4.png?raw=True)

8. Select the "ActivityAssertUnitTest" from the right hand pane and click install. If the activity is not visible in the right hand pane make sure that the "Filter Activities" check box is unchecked.

    ![Alt text](images/5.png?raw=True)

The custom activity has been loaded in the UiPath Studio.

While using this activity make sure that "ActivityAssertUnitTest" namespace has been imported. If not so you can do it by following the below steps.

1. Open workflow where you want to use this activity.

1. At the bottom of the page click "Imports".

1. In the search bar enter "ActivityAssertUnitTest" and click it to import this namespace.