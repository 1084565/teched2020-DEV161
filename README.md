# DEV161 - Extend SAP S/4HANA with a Custom UI on SAP Cloud Platform

## Description

This branch of the repository contains the code of the app at the end of exercise 7 "Run the app on CF". This code serves as the starting point for exercise 8 "Apply CI/CD to SAP Fiori Development on SAP Cloud Platform - GitHub Setup". 

## Exercise 1 - Download the Branch's Zip

1. Click the *Code* drop down, and select `Download ZIP`.

## Exercise 2 - Project Cleanup in SAP Business Application Studio

1. From the SAP Business Application Studio menu bar select *File | Open Workspace...*.

2. Select *projects*, and click *Open*.

3. Right click and folder in the workspace, and click *delete*. Click *OK* when the dialog that asks "Do you really want to delete data?" pops up.
    >There should be only two folders: *products-inventory* and *data*.

## Exercise 3 - Upload the Code to SAP Business Application Studio

1. Go to where the zip was downloaded.

2. Extract the files.

3. locate the folder *products-inventory*.

4. Drag and drop the folder to the *Explorer* view in SAP Business Application Studio.

## Exercise 3 - Final Preparations

1. From the SAP Business Application Studio menu bar select *File | Open Workspace...*.

2. Select *products-inventory*, and click *Open*.

3. Open a new terminal using [CTRL] + ~ keyboard shortcut or *Terminal | New Terminal* from the menu bar.

4. Change directory to the `productsinventory` folder.

5. In the terminal, run the following command.
    ```CLI
    npm install
    ```

## Exercise 4 - Return to Exercise 8

Click [here](https://github.com/SAP-samples/teched2020-DEV161/tree/main/exercises/ex8).


## Summary

You're good to go with exercise 8 "Apply CI/CD to SAP Fiori Development on SAP Cloud Platform - GitHub Setup" in the `main` branch.

## License
Copyright (c) 2020 SAP SE or an SAP affiliate company. All rights reserved. This file is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSES/Apache-2.0.txt) file.
