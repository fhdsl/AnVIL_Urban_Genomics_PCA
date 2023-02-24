# Instructor Guide {-}

## Lesson Plan  {-}

Coming soon!

## Notes for Instructors {-}

This R-based activity can be run on a different platform, such as your own personal installation of [R](https://www.r-project.org/) or [Posit](https://posit.co/)(formerly called RStudio), depending on your needs. 

More Coming soon!

## Checklist for Running the Activity on AnVIL {-}

### Before the class begins

This checklist can serve as a reminder of the overall suggested steps to run an activity on AnVIL. You might find yourself changing these steps slightly as you become more familiar with AnVIL.

**Billing**

- Obtain funding through the [STRIDES](https://datascience.nih.gov/strides) program (optional)
- Request students make AnVIL IDs (Google IDs) 
- Collect AnVIL IDs (Google IDs) from students
- Create Google Billing Account for your class

**Resources**

- Create a Workspace for your class (optional)
- Notify Terra of your course dates and times
- Direct students to the Workspace (either newly created or premade)

**Permissions**

- Set up Groups to manage permissions

| AnVIL Group         | Class Workspace | Terra Billing Projects*|
|:--------------------|:----------------|:-----------------------|
| Instructor          | Owner           | Owner                  |
| Teaching assistants | Writer          | Owner                  |
| Students            | Reader          | User                   |


### After the class ends

**Resources**

- Remind students to download any files they might need
- Tell students to delete their environments and persistent disks

**Billing**

- Deactivate billing project


## Setting up Billing on AnVIL {-}

The following will help you set up billing for your class. You will:  
* Set up a billing project for tracking costs
* Add yourself and students to the billing project to grant permission to AnVIL resources
* Learn about different sources of costs in AnVIL
* Estimate costs for your class
* Learn about how to track costs during your class

### Creating a billing project {#billing-project}

First, create the Billing Project. Billing Project names must be globally unique and cannot exceed 30 characters. We suggest the name of the Billing Project should be a combination of institution-class- (e.g., "jhu-bmr2021-bill-1"). To create a Billing Project:

1. Go to https://anvil.terra.bio/#billing

1. Click “+CREATE”

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_gdb96a00840_0_88.png" title="Screenshot of the Terra Billing page. The &quot;+CREATE&quot; button is highlighted." alt="Screenshot of the Terra Billing page. The &quot;+CREATE&quot; button is highlighted." width="480" />

1. Type in your Billing Project name

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_gdb96a00840_0_98.png" title="Screenshot of the Terra Billing page with Create Billing Project pop out box. The new billing project name, jhu-bmr2021-instructors-bill-1, is highlighted." alt="Screenshot of the Terra Billing page with Create Billing Project pop out box. The new billing project name, jhu-bmr2021-instructors-bill-1, is highlighted." width="480" />
    
1. Select the appropriate Billing Account

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g100474897dd_0_2.png" title="Screenshot of the Terra Billing page with Create Billing Project pop out box. The appropriate billing account name, My Billing Account, is highlighted." alt="Screenshot of the Terra Billing page with Create Billing Project pop out box. The appropriate billing account name, My Billing Account, is highlighted." width="480" />
    
1. Click “CREATE BILLING PROJECT”

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g100474897dd_0_9.png" title="Screenshot of the Terra Billing page with Create Billing Project pop out box. The &quot;CREATE BILLING PROJECT&quot; button is highlighted." alt="Screenshot of the Terra Billing page with Create Billing Project pop out box. The &quot;CREATE BILLING PROJECT&quot; button is highlighted." width="480" />
    
You now have a unique **Billing Project**.

### Adding Instructors as “Owner”

Next, you want to give instructors permission to use the Billing Project to compute. To set instructor permissions:

1. Go to https://anvil.terra.bio/#billing

1. Select the “Owned by You” Billing Project sub-list

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g1007b9b3ffb_0_0.png" title="Screenshot of the AnVIL Billing page. The &quot;Owned by You&quot; billing list is highlighted." alt="Screenshot of the AnVIL Billing page. The &quot;Owned by You&quot; billing list is highlighted." width="480" />

1. Select the Billing Project you made in [Instructor Billing Project](#billing-project)

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g1007b9b3ffb_0_10.png" title="Screenshot of the AnVIL Billing page. The &quot;Owned by You&quot; billing list has been expanded. The instructor Billing project, in this case jhu-bmr2021-instructors, is highlighted." alt="Screenshot of the AnVIL Billing page. The &quot;Owned by You&quot; billing list has been expanded. The instructor Billing project, in this case jhu-bmr2021-instructors, is highlighted." width="480" />

1. Select the “Users” tab

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g1007b9b3ffb_0_24.png" title="Screenshot of the AnVIL Billing page. The instructor Billing project, in this case jhu-bmr2021-instructors, has been selected and the Users Tab is highlighted." alt="Screenshot of the AnVIL Billing page. The instructor Billing project, in this case jhu-bmr2021-instructors, has been selected and the Users Tab is highlighted." width="480" />

1. Click “+ Add User”. You will be prompted to add a “User email *”.

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g1007b9b3ffb_0_39.png" title="Screenshot of the AnVIL Billing page. The instructor Billing project, in this case jhu-bmr2021-instructors, has been selected and the &quot;+Add User&quot; button is highlighted." alt="Screenshot of the AnVIL Billing page. The instructor Billing project, in this case jhu-bmr2021-instructors, has been selected and the &quot;+Add User&quot; button is highlighted." width="480" />

1. Begin typing the instructor Group name set up in [Instructor Group](#instructor-group). You should see an email in the form <group-name>@firecloud.org (e.g., jhu-bmr2021-instructors@firecloud.org).

1. Ensure “Can manage users (Owner)” is **selected**

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g1007b9b3ffb_0_54.png" title="Screenshot of the AnVIL Billing page with the &quot;Add User&quot; pop out box. The instructor Group email, in this case jhu-bmr2021-instructors@firecloud.org, has been filled in and the Owner role checkbox has been ticked." alt="Screenshot of the AnVIL Billing page with the &quot;Add User&quot; pop out box. The instructor Group email, in this case jhu-bmr2021-instructors@firecloud.org, has been filled in and the Owner role checkbox has been ticked." width="480" />

1. Click “ADD USER”

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g1007b9b3ffb_0_70.png" title="Screenshot of the AnVIL Billing page with the &quot;Add User&quot; pop out box. The instructor Group email, in this case jhu-bmr2021-instructors@firecloud.org, has been filled in and the Owner role checkbox has been ticked. The &quot;ADD USER&quot; button is highlighted." alt="Screenshot of the AnVIL Billing page with the &quot;Add User&quot; pop out box. The instructor Group email, in this case jhu-bmr2021-instructors@firecloud.org, has been filled in and the Owner role checkbox has been ticked. The &quot;ADD USER&quot; button is highlighted." width="480" />


::: {.notice}
This step makes it so that co-instructors can edit permissions and administer the Billing Project as needed. While this means you and co-instructors can compute using the student Billing Project, this makes spending difficult to track. Instructors should always use the **instructor Workspace** to compute. This makes it much easier to track costs associated with instructors versus students.
:::

### Adding Students as “User”

Next, you will add your student Group to the Billing Project so that they can compute. To set student permissions:

1. Go to https://anvil.terra.bio/#billing

1. Select the “Owned by You” Billing Project sub-list

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g1007b9b3ffb_0_0.png" title="Screenshot of the AnVIL Billing page. The &quot;Owned by You&quot; billing list is highlighted." alt="Screenshot of the AnVIL Billing page. The &quot;Owned by You&quot; billing list is highlighted." width="480" />

1. Select the Billing Project you made in [Billing Project](#billing-project)

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g1007b9b3ffb_0_90.png" title="Screenshot of the AnVIL Billing page. The &quot;Owned by You&quot; billing list has been expanded. The student Billing project, in this case jhu-bmr2021-students, is highlighted." alt="Screenshot of the AnVIL Billing page. The &quot;Owned by You&quot; billing list has been expanded. The student Billing project, in this case jhu-bmr2021-students, is highlighted." width="480" />

1. Select the “Users” tab

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g1007b9b3ffb_0_301.png" title="Screenshot of the AnVIL Billing page. The student Billing project, in this case jhu-bmr2021-students, has been selected and the Users Tab is highlighted." alt="Screenshot of the AnVIL Billing page. The student Billing project, in this case jhu-bmr2021-students, has been selected and the Users Tab is highlighted." width="480" />

1. Click “+ Add User”. You will be prompted to add a “User email *”.

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g1007b9b3ffb_0_315.png" title="Screenshot of the AnVIL Billing page. The student Billing project, in this case jhu-bmr2021-students, has been selected and the &quot;+Add User&quot; button is highlighted." alt="Screenshot of the AnVIL Billing page. The student Billing project, in this case jhu-bmr2021-students, has been selected and the &quot;+Add User&quot; button is highlighted." width="480" />

1. Begin typing the student Group name set up in [Student Group](#student-group). You should see an email in the form <group-name>@firecloud.org (e.g., jhu-bmr2021-students@firecloud.org). 

1. Keep “Can manage users (Owner)” **deselected**.

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g1007b9b3ffb_0_132.png" title="Screenshot of the AnVIL Billing page with the &quot;Add User&quot; pop out box. The student Group email, in this case jhu-bmr2021-students@firecloud.org, has been filled in and the Owner role checkbox has NOT been ticked." alt="Screenshot of the AnVIL Billing page with the &quot;Add User&quot; pop out box. The student Group email, in this case jhu-bmr2021-students@firecloud.org, has been filled in and the Owner role checkbox has NOT been ticked." width="480" />

1. Click “ADD USER”

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g1007b9b3ffb_0_327.png" title="Screenshot of the AnVIL Billing page with the &quot;Add User&quot; pop out box. The student Group email, in this case jhu-bmr2021-students@firecloud.org, has been filled in and the Owner role checkbox has NOT been ticked. The &quot;ADD USER&quot; button is highlighted." alt="Screenshot of the AnVIL Billing page with the &quot;Add User&quot; pop out box. The student Group email, in this case jhu-bmr2021-students@firecloud.org, has been filled in and the Owner role checkbox has NOT been ticked. The &quot;ADD USER&quot; button is highlighted." width="480" />

### Understanding the various billing costs

Costs in AnVIL fall into one of three categories: compute costs, storage costs, and network usage (egress) costs. **Compute costs** are those that students accrue when actively using an AnVIL Workspace. Students can clone a Workspace for no cost, but they will begin to accrue costs as soon as they set up a cloud environment. Compute costs are based on how many CPUs you need, as well as how much memory and storage space you choose. You can also pause the Workspace and pay a lower cost per hour than if you were to keep the Workspace running. Current prices can be found [here](https://cloud.google.com/compute/all-pricing#top_of_page).

**Storage costs** are driven by the persistent disk. The persistent disk allows you to store data and installed programs/libraries for a low cost. Students can delete their Workspaces but maintain their persistent disk so they still have access to previous programs they have installed and previous files they've created. Current prices can be found [here](https://cloud.google.com/storage/pricing#storage-pricing%20and%20https://cloud.google.com/compute/all-pricing#localssdpricing).

Finally, **network usage** costs are those involved with transferring data between networks or downloading data from the cloud to your local computer. Current prices can be found [here](https://cloud.google.com/storage/pricing#network-egress).

### Estimating costs before the class begins

AnVIL has a free [AnVIL_Cost_Estimator](https://docs.google.com/spreadsheets/d/1GUN93HDRqDbZ0uktaZjoP-y8Ril1T_VIJnQrjRD6tV4) that allows you estimate compute, storage, and network usage costs for your class. This is a Google sheet that you can tailor to fit your needs. Before you use it, make sure the prices are up to date by following the links at the bottom of the sheet. 

If you need to create a Budget Justification for your class, you can also use the free [AnVIL_Budget_Justification](https://docs.google.com/document/d/145JFLn2hviLmaYF-mO06gbCkG0i4HRaWvkUBKORo85Y/edit) template. 

### How much does a class cost?

One of the advantages of billing projects in Terra is that you can keep track of the costs during real time. You can see how much each Workspace is costing while your course is happening, so there are no unexpected surprises at the end!

Full details about billing in Terra can be found [here](https://support.terra.bio/hc/en-us/articles/4405325218075). These instructions are adapted from Terra Support.

To view the costs being accrued by each billing project, you can go to [https://console.cloud.google.com/billing](https://console.cloud.google.com/billing). At the top of the page, there is a dropdown menu. Choose the billing project name you'd like to view.


<img src="resources/images/04_billing/billing_1.png" title="Locating dropdown menu" alt="Locating dropdown menu" style="display: block; margin: auto;" />


Once you are in proper billing project, you click on "View detailed charges" in the Billing section on the far right.


<img src="resources/images/04_billing/billing_2.png" title="Locating detailed charges" alt="Locating detailed charges" style="display: block; margin: auto;" />


This takes you to a report of the detailed charges accrued by the billing account. Here, you will be able to see the total cost over a time range, as well as costs broken down by services.


<img src="resources/images/04_billing/billing_3.png" title="Locating dropdown menu" alt="Locating dropdown menu" style="display: block; margin: auto;" />


## Setting up the Class Activity {-}

### Overview of Class Setup

This section will show you how to organize your class to make it easier to administer access to your content. You will need to have a list of who will be taking your class, such as a course roster or sign-up list, as well as a list of additional instructors or teaching assistants. You can make changes later, so the list of students need not be final.

### Collect Google IDs

AnVIL IDs are based on [Google accounts](account-setup.html#google-account).

Students -- Contact students/participants to get their AnVIL IDs. These should be Gmail addresses or emails with GSuite capabilities. You can link students to [Student Account Setup](student-account-setup.html) for instructions on what they should do.

Co-instructors -- If you will be working with other instructors, such as co-instructors or teaching assistants, you will need to collect their IDs as well.

### Set Up Groups
Reminder:

- Google **Billing Accounts** are managed on Google Cloud Platform and are used for organizing *funding sources* (e.g. credit cards, cloud credits).
- Terra **Billing Projects** are managed through Terra, and allow you to associate your Terra activity with the correct Google Billing Account.

For a more detailed explanation, please see the chapter on Account Setup.

We suggest creating two different Terra Billing Projects under the appropriate Billing Account that you created on `cloud.google.com`: one for students and one for co-instructors. The instructions below will walk you through how to set this up.

Groups enable you to share your class Workspace and manage permissions for many people at once. We recommend starting with one Group for instructors and one Group for students.

#### Instructor Group {#instructor-group}

Create an informative, unique Group name for any co-instructors and teaching assistants. We suggest a combination of institution-class-role (e.g., “jhu-bmr2021-instructors”). Only letters, numbers, underscores, and dashes are allowed in Group names. To create a Group for instructors:

1. Go to https://anvil.terra.bio/#groups

1. Click “+ Create a New Group”

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_gdb96a00840_0_6.png" title="Screenshot of the Terra Group page. The &quot;Create a New Group&quot; button is highlighted." alt="Screenshot of the Terra Group page. The &quot;Create a New Group&quot; button is highlighted." width="480" />

1. Type in your instructor Group name

1. Click “CREATE GROUP”

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_gdb96a00840_0_16.png" title="Screenshot of the Terra Group page with Create New Group pop out box. The Group name, jhu-bmr2021-instructors, has been entered and the &quot;CREATE GROUP&quot; button is highlighted." alt="Screenshot of the Terra Group page with Create New Group pop out box. The Group name, jhu-bmr2021-instructors, has been entered and the &quot;CREATE GROUP&quot; button is highlighted." width="480" />

You now have a unique **instructor Group**.

##### Add Instructors as "Admin" (Instructor Group)

Now that your instructor Group has been created, you should add any additional instructors. You should also ensure that they have the correct permissions. 

1. Go to https://anvil.terra.bio/#groups/ and click on the instructor Group name. This page should also be visible at `https://anvil.terra.bio/#groups/<group-name>`.

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g10118383b73_193_0.png" title="Screenshot of the Terra Group, and the specific Group that was just created. The Group Name is highlighted." alt="Screenshot of the Terra Group, and the specific Group that was just created. The Group Name is highlighted." width="480" />

1. Click on “+Add User”. You will be prompted to add the instructor’s AnVIL ID. 

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g100474897dd_0_45.png" title="Screenshot of the Terra Group page for the specific Group that was just created. The &quot;+Add User&quot; button is highlighted." alt="Screenshot of the Terra Group page for the specific Group that was just created. The &quot;+Add User&quot; button is highlighted." width="480" />

1. Type in the instructor’s AnVIL ID

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g100474897dd_0_58.png" title="Screenshot of the Terra Group for the specific Group that was just created, with &quot;Add user to Terra Group&quot; pop out box. The instructor`s AnVIL ID, instructor-1@gmail.com, has been entered and the AnVIL ID (email) is highlighted." alt="Screenshot of the Terra Group for the specific Group that was just created, with &quot;Add user to Terra Group&quot; pop out box. The instructor`s AnVIL ID, instructor-1@gmail.com, has been entered and the AnVIL ID (email) is highlighted." width="480" />

1. Make sure “Can manage users (admin)” is **selected**

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g100474897dd_0_65.png" title="Screenshot of the Terra Group for the specific Group that was just created, with &quot;Add user to Terra Group&quot; pop out box. The instructor`s AnVIL ID, instructor-1@gmail.com, has been entered and the checkbox &quot;Can manage users (admin)&quot; has been selected and is highlighted." alt="Screenshot of the Terra Group for the specific Group that was just created, with &quot;Add user to Terra Group&quot; pop out box. The instructor`s AnVIL ID, instructor-1@gmail.com, has been entered and the checkbox &quot;Can manage users (admin)&quot; has been selected and is highlighted." width="480" />

1. Click ADD USER. This will take you back to the Group administration page.

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g100474897dd_0_71.png" title="Screenshot of the Terra Group for the specific Group that was just created, with &quot;Add user to Terra Group&quot; pop out box. The instructor`s AnVIL ID, instructor-1@gmail.com, has been entered and the &quot;ADD USER&quot; button is highlighted." alt="Screenshot of the Terra Group for the specific Group that was just created, with &quot;Add user to Terra Group&quot; pop out box. The instructor`s AnVIL ID, instructor-1@gmail.com, has been entered and the &quot;ADD USER&quot; button is highlighted." width="480" />

Make sure the newly added instructor displays “Admin” under “Roles” beside their AnVIL ID. Repeat this process for any additional co-instructors and teaching assistants.

<img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g100474897dd_0_78.png" title="Screenshot of the Terra Group for the instructor Group that was just created, where the newly added instructor is visible in the user list. The instructor`s AnVIL ID, instructor-1@gmail.com is visible next to the role &quot;Admin&quot;, which is highlighted." alt="Screenshot of the Terra Group for the instructor Group that was just created, where the newly added instructor is visible in the user list. The instructor`s AnVIL ID, instructor-1@gmail.com is visible next to the role &quot;Admin&quot;, which is highlighted." width="480" />

#### Student Group {#student-group}

Next, you will create a Group for your students. Create an informative, unique Group name. We suggest a combination of institution-class-role (e.g., “jhu-bmr2021-students”). Only letters, numbers, underscores, and dashes are allowed in Group names. To create a Group for students:

1. Go to https://anvil.terra.bio/#groups

1. Click “+ Create a New Group”

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_gdb96a00840_0_6.png" title="Screenshot of the Terra Group page. The &quot;Create a New Group&quot; button is highlighted." alt="Screenshot of the Terra Group page. The &quot;Create a New Group&quot; button is highlighted." width="480" />

1. Type in your student Group name

1. Click “CREATE GROUP”

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g100474897dd_0_38.png" title="Screenshot of the Terra Group page with Create New Group pop out box. The Group name, jhu-bmr2021-students, has been entered and the &quot;CREATE GROUP&quot; button is highlighted." alt="Screenshot of the Terra Group page with Create New Group pop out box. The Group name, jhu-bmr2021-students, has been entered and the &quot;CREATE GROUP&quot; button is highlighted." width="480" />

You now have a unique **student Group**.

##### Add Instructors as "Admin" (Student Group)

The next steps ensure any additional co-instructors and teaching assistants are able to administer the student Group in case you are unavailable. Follow the steps below to add each co-instructor in the student Group:

1. Go to https://anvil.terra.bio/#groups/ and click on the student Group name. This page should be visible at `https://anvil.terra.bio/#groups/<group-name>`.

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g10118383b73_193_8.png" title="Screenshot of the Terra Group, and the specific Group that was just created. The student Group name is highlighted." alt="Screenshot of the Terra Group, and the specific Group that was just created. The student Group name is highlighted." width="480" />

1. Click on “+Add User”. You will be prompted to add the instructor’s AnVIL ID. 

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g100474897dd_0_104.png" title="Screenshot of the Terra Group page for the specific Group that was just created. The &quot;+Add User&quot; button is highlighted." alt="Screenshot of the Terra Group page for the specific Group that was just created. The &quot;+Add User&quot; button is highlighted." width="480" />

1. Type in the instructor’s AnVIL ID

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g100474897dd_0_58.png" title="Screenshot of the Terra Group for the specific Group that was just created, with &quot;Add user to Terra Group&quot; pop out box. The instructor`s AnVIL ID, instructor-1@gmail.com, has been entered and the AnVIL ID (email) is highlighted." alt="Screenshot of the Terra Group for the specific Group that was just created, with &quot;Add user to Terra Group&quot; pop out box. The instructor`s AnVIL ID, instructor-1@gmail.com, has been entered and the AnVIL ID (email) is highlighted." width="480" />

1. Make sure “Can manage users (admin)” is **selected**

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g100474897dd_0_65.png" title="Screenshot of the Terra Group for the specific Group that was just created, with &quot;Add user to Terra Group&quot; pop out box. The instructor`s AnVIL ID, instructor-1@gmail.com, has been entered and the checkbox &quot;Can manage users (admin)&quot; has been selected and is highlighted." alt="Screenshot of the Terra Group for the specific Group that was just created, with &quot;Add user to Terra Group&quot; pop out box. The instructor`s AnVIL ID, instructor-1@gmail.com, has been entered and the checkbox &quot;Can manage users (admin)&quot; has been selected and is highlighted." width="480" />

1. Click ADD USER. This will take you back to the Group administration page.

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g100474897dd_0_71.png" title="Screenshot of the Terra Group for the specific Group that was just created, with &quot;Add user to Terra Group&quot; pop out box. The instructor`s AnVIL ID, instructor-1@gmail.com, has been entered and the &quot;ADD USER&quot; button is highlighted." alt="Screenshot of the Terra Group for the specific Group that was just created, with &quot;Add user to Terra Group&quot; pop out box. The instructor`s AnVIL ID, instructor-1@gmail.com, has been entered and the &quot;ADD USER&quot; button is highlighted." width="480" />

Make sure the newly added instructor displays “Admin” under “Roles” beside their AnVIL ID. Repeat this process for any additional co-instructors and teaching assistants.

<img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g100474897dd_0_87.png" title="Screenshot of the Terra Group for the student Group that was just created, where the newly added instructor is visible in the user list. The instructor`s AnVIL ID, instructor-1@gmail.com is visible next to the role &quot;Admin&quot;, which is highlighted." alt="Screenshot of the Terra Group for the student Group that was just created, where the newly added instructor is visible in the user list. The instructor`s AnVIL ID, instructor-1@gmail.com is visible next to the role &quot;Admin&quot;, which is highlighted." width="480" />

##### Add Students as "Member"

Follow the steps below to add individual students to the student Group:

1. Go to https://anvil.terra.bio/#groups/ and click on the student Group name. This page should be visible at `https://anvil.terra.bio/#groups/<group-name>`.

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g10118383b73_193_8.png" title="Screenshot of the Terra Group, and the specific Group that was just created. The student Group name is highlighted." alt="Screenshot of the Terra Group, and the specific Group that was just created. The student Group name is highlighted." width="480" />

1. Click on “+Add User”. You will be prompted to add an AnVIL ID. 

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g100474897dd_0_104.png" title="Screenshot of the Terra Group page for the specific Group that was just created. The &quot;+Add User&quot; button is highlighted." alt="Screenshot of the Terra Group page for the specific Group that was just created. The &quot;+Add User&quot; button is highlighted." width="480" />

1. Type in the student’s AnVIL ID

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g100474897dd_0_111.png" title="Screenshot of the Terra Group for the specific Group that was just created, with &quot;Add user to Terra Group&quot; pop out box. The student`s AnVIL ID, student-1@gmail.com, has been entered and the AnVIL ID (email) is highlighted." alt="Screenshot of the Terra Group for the specific Group that was just created, with &quot;Add user to Terra Group&quot; pop out box. The student`s AnVIL ID, student-1@gmail.com, has been entered and the AnVIL ID (email) is highlighted." width="480" />

1. Click ADD USER

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g100474897dd_0_117.png" title="Screenshot of the Terra Group for the specific Group that was just created, with &quot;Add user to Terra Group&quot; pop out box. The student`s AnVIL ID, student-1@gmail.com, has been entered and the &quot;ADD USER&quot; button is highlighted." alt="Screenshot of the Terra Group for the specific Group that was just created, with &quot;Add user to Terra Group&quot; pop out box. The student`s AnVIL ID, student-1@gmail.com, has been entered and the &quot;ADD USER&quot; button is highlighted." width="480" />

Make sure the newly added student displays “Member” under “Roles” beside their AnVIL ID. At present, each student’s AnVIL ID must be added separately.

<img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g100474897dd_0_125.png" title="Screenshot of the Terra Group for the student Group that was just created, where the newly added student is visible in the user list. The student`s AnVIL ID, student-1@gmail.com is visible next to the role &quot;Member&quot;, which is highlighted." alt="Screenshot of the Terra Group for the student Group that was just created, where the newly added student is visible in the user list. The student`s AnVIL ID, student-1@gmail.com is visible next to the role &quot;Member&quot;, which is highlighted." width="480" />

Your instructor and student Groups are now set up.

#### Group Email Lists

Note that your newly created Groups have Group emails associated with them. Take note of these Group emails. You will use them for granting access to your class Billing Projects and Workspaces in the next steps.

<img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g100474897dd_0_96.png" title="Screenshot of the Terra Group page. Emails associated with newly formed Groups have been highlighted." alt="Screenshot of the Terra Group page. Emails associated with newly formed Groups have been highlighted." width="480" />

### Set Up Billing Projects

Billing Projects in Terra help organize your compute costs. Like Groups, we suggest creating two different billing projects under the appropriate Billing Account that you created on `cloud.google.com`: one for students and one for co-instructors.

Billing Project names must be globally unique and cannot exceed 30 characters.

#### Instructor Billing Project {#instructor-billing-project}

First, create the Billing Project for instructors. We suggest the name of the Billing Project should be a combination of institution-class-role (e.g., "jhu-bmr2021-instructors-bill-1"). To create a Billing Project for instructors:

1. Go to https://anvil.terra.bio/#billing

1. Click “+CREATE”

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_gdb96a00840_0_88.png" title="Screenshot of the Terra Billing page. The &quot;+CREATE&quot; button is highlighted." alt="Screenshot of the Terra Billing page. The &quot;+CREATE&quot; button is highlighted." width="480" />

1. Type in your instructor Billing Project name

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_gdb96a00840_0_98.png" title="Screenshot of the Terra Billing page with Create Billing Project pop out box. The new billing project name, jhu-bmr2021-instructors-bill-1, is highlighted." alt="Screenshot of the Terra Billing page with Create Billing Project pop out box. The new billing project name, jhu-bmr2021-instructors-bill-1, is highlighted." width="480" />
    
1. Select the appropriate Billing Account

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g100474897dd_0_2.png" title="Screenshot of the Terra Billing page with Create Billing Project pop out box. The appropriate billing account name, My Billing Account, is highlighted." alt="Screenshot of the Terra Billing page with Create Billing Project pop out box. The appropriate billing account name, My Billing Account, is highlighted." width="480" />
    
1. Click “CREATE BILLING PROJECT”

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g100474897dd_0_9.png" title="Screenshot of the Terra Billing page with Create Billing Project pop out box. The &quot;CREATE BILLING PROJECT&quot; button is highlighted." alt="Screenshot of the Terra Billing page with Create Billing Project pop out box. The &quot;CREATE BILLING PROJECT&quot; button is highlighted." width="480" />
    
You now have a unique **instructor Billing Project**.

##### Add Instructors as “Owner” (Instructor Project)

Next, you want to give instructors permission to use the Billing Project to compute. To set instructor permissions:

1. Go to https://anvil.terra.bio/#billing

1. Select the “Owned by You” Billing Project sub-list

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g1007b9b3ffb_0_0.png" title="Screenshot of the AnVIL Billing page. The &quot;Owned by You&quot; billing list is highlighted." alt="Screenshot of the AnVIL Billing page. The &quot;Owned by You&quot; billing list is highlighted." width="480" />

1. Select the Billing Project you made for instructors in [Instructor Billing Project](#instructor-billing-project)

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g1007b9b3ffb_0_10.png" title="Screenshot of the AnVIL Billing page. The &quot;Owned by You&quot; billing list has been expanded. The instructor Billing project, in this case jhu-bmr2021-instructors, is highlighted." alt="Screenshot of the AnVIL Billing page. The &quot;Owned by You&quot; billing list has been expanded. The instructor Billing project, in this case jhu-bmr2021-instructors, is highlighted." width="480" />

1. Select the “Users” tab

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g1007b9b3ffb_0_24.png" title="Screenshot of the AnVIL Billing page. The instructor Billing project, in this case jhu-bmr2021-instructors, has been selected and the Users Tab is highlighted." alt="Screenshot of the AnVIL Billing page. The instructor Billing project, in this case jhu-bmr2021-instructors, has been selected and the Users Tab is highlighted." width="480" />

1. Click “+ Add User”. You will be prompted to add a “User email *”.

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g1007b9b3ffb_0_39.png" title="Screenshot of the AnVIL Billing page. The instructor Billing project, in this case jhu-bmr2021-instructors, has been selected and the &quot;+Add User&quot; button is highlighted." alt="Screenshot of the AnVIL Billing page. The instructor Billing project, in this case jhu-bmr2021-instructors, has been selected and the &quot;+Add User&quot; button is highlighted." width="480" />

1. Begin typing the instructor Group name set up in [Instructor Group](#instructor-group). You should see an email in the form <group-name>@firecloud.org (e.g., jhu-bmr2021-instructors@firecloud.org).

1. Ensure “Can manage users (Owner)” is **selected**

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g1007b9b3ffb_0_54.png" title="Screenshot of the AnVIL Billing page with the &quot;Add User&quot; pop out box. The instructor Group email, in this case jhu-bmr2021-instructors@firecloud.org, has been filled in and the Owner role checkbox has been ticked." alt="Screenshot of the AnVIL Billing page with the &quot;Add User&quot; pop out box. The instructor Group email, in this case jhu-bmr2021-instructors@firecloud.org, has been filled in and the Owner role checkbox has been ticked." width="480" />

1. Click “ADD USER”

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g1007b9b3ffb_0_70.png" title="Screenshot of the AnVIL Billing page with the &quot;Add User&quot; pop out box. The instructor Group email, in this case jhu-bmr2021-instructors@firecloud.org, has been filled in and the Owner role checkbox has been ticked. The &quot;ADD USER&quot; button is highlighted." alt="Screenshot of the AnVIL Billing page with the &quot;Add User&quot; pop out box. The instructor Group email, in this case jhu-bmr2021-instructors@firecloud.org, has been filled in and the Owner role checkbox has been ticked. The &quot;ADD USER&quot; button is highlighted." width="480" />

Your **instructor Billing Project** is now set up.

#### Student Billing Project {#student-billing-project}

Next, create a student Billing Project. Again, we suggest a combination of institution-class-role (e.g., “jhu-bmr2021-students-bill-1”). To create a Billing Project for students:

1. Go to https://anvil.terra.bio/#billing 

1. Click “+CREATE”

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_gdb96a00840_0_88.png" title="Screenshot of the Terra Billing page. The &quot;+CREATE&quot; button is highlighted." alt="Screenshot of the Terra Billing page. The &quot;+CREATE&quot; button is highlighted." width="480" />
    
1. Type in your student Billing Project name

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g100474897dd_0_15.png" title="Screenshot of the Terra Billing page with Create Billing Project pop out box. The new billing project name, jhu-bmr2021-students-bill-1, is highlighted." alt="Screenshot of the Terra Billing page with Create Billing Project pop out box. The new billing project name, jhu-bmr2021-students-bill-1, is highlighted." width="480" />
    
1. Select the appropriate Billing Account (same as above)

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g100474897dd_0_21.png" title="Screenshot of the Terra Billing page with Create Billing Project pop out box. The appropriate billing account name, My Billing Account, is highlighted." alt="Screenshot of the Terra Billing page with Create Billing Project pop out box. The appropriate billing account name, My Billing Account, is highlighted." width="480" />

1. Click “CREATE BILLING PROJECT”

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g100474897dd_0_27.png" title="Screenshot of the Terra Billing page with Create Billing Project pop out box. The &quot;CREATE BILLING PROJECT&quot; button is highlighted." alt="Screenshot of the Terra Billing page with Create Billing Project pop out box. The &quot;CREATE BILLING PROJECT&quot; button is highlighted." width="480" />

You now have a unique **student Billing Project**.
   
##### Add Instructors as “Owner” (Student Project)

You want to ensure any additional co-instructors and teaching assistants are able to administer the student Billing Project in case you are unavailable. To set instructor permissions:

1. Go to https://anvil.terra.bio/#billing

1. Select the “Owned by You” Billing Project sub-list

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g1007b9b3ffb_0_0.png" title="Screenshot of the AnVIL Billing page. The &quot;Owned by You&quot; billing list is highlighted." alt="Screenshot of the AnVIL Billing page. The &quot;Owned by You&quot; billing list is highlighted." width="480" />

1. Select the Billing Project you made for students in [Student Billing Project](#student-billing-project)

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g1007b9b3ffb_0_90.png" title="Screenshot of the AnVIL Billing page. The &quot;Owned by You&quot; billing list has been expanded. The student Billing project, in this case jhu-bmr2021-students, is highlighted." alt="Screenshot of the AnVIL Billing page. The &quot;Owned by You&quot; billing list has been expanded. The student Billing project, in this case jhu-bmr2021-students, is highlighted." width="480" />

1. Select the “Users” tab

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g1007b9b3ffb_0_301.png" title="Screenshot of the AnVIL Billing page. The student Billing project, in this case jhu-bmr2021-students, has been selected and the Users Tab is highlighted." alt="Screenshot of the AnVIL Billing page. The student Billing project, in this case jhu-bmr2021-students, has been selected and the Users Tab is highlighted." width="480" />

1. Click “+ Add User”. You will be prompted to add a “User email *”.

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g1007b9b3ffb_0_315.png" title="Screenshot of the AnVIL Billing page. The student Billing project, in this case jhu-bmr2021-students, has been selected and the &quot;+Add User&quot; button is highlighted." alt="Screenshot of the AnVIL Billing page. The student Billing project, in this case jhu-bmr2021-students, has been selected and the &quot;+Add User&quot; button is highlighted." width="480" />

1. Begin typing the instructor Group name set up in [### Set Up Groups]. You should see an email in the form <group-name>@firecloud.org (e.g., jhu-bmr2021-instructors@firecloud.org).

1. Ensure “Can manage users (Owner)” is **selected**

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g1007b9b3ffb_0_54.png" title="Screenshot of the AnVIL Billing page with the &quot;Add User&quot; pop out box. The instructor Group email, in this case jhu-bmr2021-instructors@firecloud.org, has been filled in and the Owner role checkbox has been ticked." alt="Screenshot of the AnVIL Billing page with the &quot;Add User&quot; pop out box. The instructor Group email, in this case jhu-bmr2021-instructors@firecloud.org, has been filled in and the Owner role checkbox has been ticked." width="480" />

1. Click “ADD USER”

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g1007b9b3ffb_0_70.png" title="Screenshot of the AnVIL Billing page with the &quot;Add User&quot; pop out box. The instructor Group email, in this case jhu-bmr2021-instructors@firecloud.org, has been filled in and the Owner role checkbox has been ticked. The &quot;ADD USER&quot; button is highlighted." alt="Screenshot of the AnVIL Billing page with the &quot;Add User&quot; pop out box. The instructor Group email, in this case jhu-bmr2021-instructors@firecloud.org, has been filled in and the Owner role checkbox has been ticked. The &quot;ADD USER&quot; button is highlighted." width="480" />
    
::: {.notice}
This step makes it so that co-instructors can edit permissions and administer the student Billing Project as needed. While this means you and co-instructors can compute using the student Billing Project, this makes spending difficult to track. Instructors should always use the **instructor Billing Project** to compute. This makes it much easier to track costs associated with instructors versus students.
:::

##### Add Students as “User”

Next, you will add your student Group to the student Billing Project so that they can compute. To set student permissions:

1. Go to https://anvil.terra.bio/#billing

1. Select the “Owned by You” Billing Project sub-list

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g1007b9b3ffb_0_0.png" title="Screenshot of the AnVIL Billing page. The &quot;Owned by You&quot; billing list is highlighted." alt="Screenshot of the AnVIL Billing page. The &quot;Owned by You&quot; billing list is highlighted." width="480" />

1. Select the Billing Project you made for students in [Student Billing Project](#student-billing-project)

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g1007b9b3ffb_0_90.png" title="Screenshot of the AnVIL Billing page. The &quot;Owned by You&quot; billing list has been expanded. The student Billing project, in this case jhu-bmr2021-students, is highlighted." alt="Screenshot of the AnVIL Billing page. The &quot;Owned by You&quot; billing list has been expanded. The student Billing project, in this case jhu-bmr2021-students, is highlighted." width="480" />

1. Select the “Users” tab

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g1007b9b3ffb_0_301.png" title="Screenshot of the AnVIL Billing page. The student Billing project, in this case jhu-bmr2021-students, has been selected and the Users Tab is highlighted." alt="Screenshot of the AnVIL Billing page. The student Billing project, in this case jhu-bmr2021-students, has been selected and the Users Tab is highlighted." width="480" />

1. Click “+ Add User”. You will be prompted to add a “User email *”.

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g1007b9b3ffb_0_315.png" title="Screenshot of the AnVIL Billing page. The student Billing project, in this case jhu-bmr2021-students, has been selected and the &quot;+Add User&quot; button is highlighted." alt="Screenshot of the AnVIL Billing page. The student Billing project, in this case jhu-bmr2021-students, has been selected and the &quot;+Add User&quot; button is highlighted." width="480" />

1. Begin typing the student Group name set up in [Student Group](#student-group). You should see an email in the form <group-name>@firecloud.org (e.g., jhu-bmr2021-students@firecloud.org). 

1. Keep “Can manage users (Owner)” **deselected**.

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g1007b9b3ffb_0_132.png" title="Screenshot of the AnVIL Billing page with the &quot;Add User&quot; pop out box. The student Group email, in this case jhu-bmr2021-students@firecloud.org, has been filled in and the Owner role checkbox has NOT been ticked." alt="Screenshot of the AnVIL Billing page with the &quot;Add User&quot; pop out box. The student Group email, in this case jhu-bmr2021-students@firecloud.org, has been filled in and the Owner role checkbox has NOT been ticked." width="480" />

1. Click “ADD USER”

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g1007b9b3ffb_0_327.png" title="Screenshot of the AnVIL Billing page with the &quot;Add User&quot; pop out box. The student Group email, in this case jhu-bmr2021-students@firecloud.org, has been filled in and the Owner role checkbox has NOT been ticked. The &quot;ADD USER&quot; button is highlighted." alt="Screenshot of the AnVIL Billing page with the &quot;Add User&quot; pop out box. The student Group email, in this case jhu-bmr2021-students@firecloud.org, has been filled in and the Owner role checkbox has NOT been ticked. The &quot;ADD USER&quot; button is highlighted." width="480" />

Your **student Billing Project** is now set up.

### Set Permissions - Workspace

Finally, you will want to set up permissions for co-instructors and students to see the class Workspace you created with the development Billing Project in [Developing Content](developing-content.html). AnVIL users can take on the "Owner", "Writer", or "Reader" role for a Workspace.

#### Add Instructors as “Owner”

You should add your co-instructors and teaching assistants as “Owners” to the class Workspace. This is useful if they need to edit the course content or share the space with students on your behalf. To share and change permissions:

1. Go to https://anvil.terra.bio/#workspaces and find your class Workspace you set up in [Developing Content](developing-content.html)

1. Click the teardrop button for your class Workspace

1. Click “Share”. This will open a dialog box.

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g1007b9b3ffb_0_344.png" title="Screenshot of the class Workspace listed in the Workspaces tab. The teardrop button and the option to &quot;Share&quot; the Workspace are highlighted." alt="Screenshot of the class Workspace listed in the Workspaces tab. The teardrop button and the option to &quot;Share&quot; the Workspace are highlighted." width="480" />

1. Enter the name of the instructor Group (e.g., jhu-bmr2021-instructors). This will create a dropdown for the Group permissions in the box. Select this Group.

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_gdb96a00840_0_138.png" title="Screenshot of the share Workspace pop out box. The text &quot;jhu-bmr&quot; has been entered in the User email box and the dropdown below has been automatically filtered to reveal the instructor, student, and dev Groups. The instructor Group, in this case jhu-bmr2021-instructors@firecloud.org, has been highlighted." alt="Screenshot of the share Workspace pop out box. The text &quot;jhu-bmr&quot; has been entered in the User email box and the dropdown below has been automatically filtered to reveal the instructor, student, and dev Groups. The instructor Group, in this case jhu-bmr2021-instructors@firecloud.org, has been highlighted." width="480" />

1. Change permissions to “Owner” using the dropdown menu under the instructor Group

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g1007b9b3ffb_0_356.png" title="Screenshot of the share Workspace pop out box. The instructor Group, in this case jhu-bmr2021-instructors@firecloud.org, has been added as a collaborator. The permissions are highlighted and show that role has been set to &quot;Owner&quot;." alt="Screenshot of the share Workspace pop out box. The instructor Group, in this case jhu-bmr2021-instructors@firecloud.org, has been added as a collaborator. The permissions are highlighted and show that role has been set to &quot;Owner&quot;." width="480" />

1. Click “SAVE”

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g1007b9b3ffb_0_365.png" title="Screenshot of the share Workspace pop out box. The instructor Group email has been added with permissions correctly set. The &quot;SAVE&quot; button is highlighted." alt="Screenshot of the share Workspace pop out box. The instructor Group email has been added with permissions correctly set. The &quot;SAVE&quot; button is highlighted." width="480" />

::: {.notice}
This step makes it so that co-instructors can edit the original content of the Workspace as needed. While this means you and co-instructors can compute using the development Billing Project, this makes spending difficult to track. Instructors should instead clone the Workspace using the **instructor Billing Project**. This makes it much easier to track costs associated with this iteration of your class versus further iterations (e.g., the following semester or year).
:::

#### Add Students as “Reader”

Next, add your students as “Readers” to the class Workspace. This means they will be able to view and clone the Workspace, but not make edits or perform computations. To share the Workspace:

1. Click the teardrop button for your class Workspace

1. Click “Share”. This will open a dialog box.

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g1007b9b3ffb_0_344.png" title="Screenshot of the class Workspace listed in the Workspaces tab. The teardrop button and the option to &quot;Share&quot; the Workspace are highlighted." alt="Screenshot of the class Workspace listed in the Workspaces tab. The teardrop button and the option to &quot;Share&quot; the Workspace are highlighted." width="480" />

1. Enter the name of the student Group. This will create a dropdown for the Group permissions in the box. Select this Group.

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g1007b9b3ffb_0_378.png" title="Screenshot of the share Workspace pop out box. The text &quot;jhu-bmr&quot; has been entered in the User email box and the dropdown below has been automatically filtered to reveal the student and dev Groups. The student Group, in this case jhu-bmr2021-students@firecloud.org, has been highlighted." alt="Screenshot of the share Workspace pop out box. The text &quot;jhu-bmr&quot; has been entered in the User email box and the dropdown below has been automatically filtered to reveal the student and dev Groups. The student Group, in this case jhu-bmr2021-students@firecloud.org, has been highlighted." width="480" />

1. Ensure permissions are set to “Reader” (default)

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g1007b9b3ffb_0_386.png" title="Screenshot of the share Workspace pop out box. The student Group, in this case jhu-bmr2021-students@firecloud.org, has been added as a collaborator. The permissions are highlighted and show that role is &quot;Reader&quot;." alt="Screenshot of the share Workspace pop out box. The student Group, in this case jhu-bmr2021-students@firecloud.org, has been added as a collaborator. The permissions are highlighted and show that role is &quot;Reader&quot;." width="480" />

1. Click “SAVE”

    <img src="02-instructor_guide_files/figure-html//1HHWg47Tg6miv_K7GNB6ZDTx-4Jc5IMl7APfFtD1Rqag_g1007b9b3ffb_0_394.png" title="Screenshot of the share Workspace pop out box. The student Group email has been added with permissions correctly set. The &quot;SAVE&quot; button is highlighted." alt="Screenshot of the share Workspace pop out box. The student Group email has been added with permissions correctly set. The &quot;SAVE&quot; button is highlighted." width="480" />

You have now correctly set up your class permissions!

### Notify Terra

Contacting Terra ahead of your class time helps the Terra team avoid any major disruptions to your class. Contact Terra by [submitting a request](https://support.terra.bio/hc/en-us/requests/new) for a hold on scheduled maintenance and downtime. It’s also a good idea to ask about major changes planned for the time prior to your class.


## Getting Credit for Professional Development {-}

We are happy to provide a letter to your supervisor, department head, or dean to indicate you've worked through this content and intend to use it in your class.
