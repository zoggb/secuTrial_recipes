# Create new project

1. Login to the CustomerAdminTool, select the customer area or define a new one. Select "new scheme/neues Schema". Create the adminuser as well as the "new scheme/neues Schema".
2. Login to the AdminTool, set you password. In the AdminTool navigate to the respective customer area and select "Participant/Teilnehmer". Select yourself as administrator and click the checkbox "Can create and edit new projects/Darf Projekte anlegen und editieren".

    ```
    Note: If the checkbox does not appear, go to the other
          admin accounts and disable the checkbox there.
    ```

3. Go to the FormBuilder and create a new project. It is automatically assigned to the new scheme.

4. Go back to the AdminTool and un-check the checkbox that allows you to create new projects. 

5. In the AdminTool: (Define at least one centre of the project.)  (Make sure to refresh the browser)<br>
    5.1 Select "centre" and create a "new centre" <br>
    5.2 Select "participant" and choose yourself as admin. Under "Projekt oder Zentrum hinzufügen" you can choose your project and enable to see the project for all the previously defined centres <br>

6. In the FormBuilder: <br>
    6.1 Select "Edit configuration". At the level "Additional patient-ID (Add-ID)" enable "instead of Pat-ID" and specify the format: e.g. NNN (Click on set) <br> 
    6.2 Select "Use project prefix" and "Use centre prefix" (This enables you to create the project-prefix in the AdminTool <br>

7. In the  AdminTool: <br> 
    7.1 Select projects, and choose your project. Under Zus-ID, Präfix/Add-ID, prefix  type your project prefix: e.g. TEST- <br>
    7.2 Select centres and choose the centre for your study. Add the  prefix for the Add-ID/ "Präfix für Zus-ID", e.g USB- <br>

This recipe was tested under secuTrial version 5.5.1.10
