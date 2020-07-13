---
id: platform-patterns
title: Patterns
---

<a id="aHeaderMenuAnchor" data-header-menu="Docs"></a>

Patterns are an essential element of Pyronome technology. Patterns are formed by bringing together the schemas -that shape the project model-, the static files, and the templates. Patterns can be based on other patterns, just like projects.

## My Patterns Page
This page lists the patterns you are a member of, or you have created. You can add new patterns or view your existing patterns on this page.

| Table Field | Description |
| ------ | ------ |
| Name | This field shows the pattern title, the folder where the pattern is located and the pattern name. |
| Active Version | Pyronome allows users to create different versions of their patterns. This field refers to the version in which the user actively makes modifications to it. The active version can be changed via the **"Versions"** page of the pattern. |
| Enabled | This field indicates whether the pattern is enabled or not. Other members cannot view disabled patterns. |
| <i class="fas fa-users"></i> Members Button | Displays the **"Members"** page, which lists other members authorized to take action on the pattern. |
| <i class="fas fa-trash-alt"></i> Delete Button | You can use this button to delete a specific pattern. |

## Installed Pattern Page
This page lists the patterns that you have included in your projects and patterns.

## New Pattern Page
This page contains the form, which you can add a new pattern.

| Form Field | Description |
| ------ | ------ |
| Enabled | Using this field, you can specify whether the pattern is enabled or not. |
| Create Empty Pattern | When this field is selected, an empty pattern is created. |
| Clone Existing Pattern | You can create a new pattern by cloning a pattern that you have already created or have permission to edit. When this field is selected, you must choose a pattern. |
| Patterns | This field is only displayed when the **"Clone Existing pattern"** field is selected. This field specifies the main pattern that the new pattern will be cloned. This field lists the patterns that you have previously created, or you have permission to edit. |
| Organization | This field specifies in which namespace that the new pattern will be created. This field lists your user name and the organizations you have added.<br><br>`Required` |
| Use Existing Directory | This field specifies that the new pattern will be created into an existing directory. |
| Create New Directory | When this field is selected, the new pattern is created in the new directory. |
| Main Directory | This field is displayed when the **"Create New Directory"** is selected. Specifies the main directory where the pattern will be created. |
| Sub Directory | This field is displayed when the **"Create New Directory"** is selected. Specifies the subdirectory where the pattern will be created. |
| Name | This field specifies the name of the new pattern.<br><i class="fas fa-exclamation-triangle"></i> Please note the criteria in the [General Settings Page](#general-settings-page) section regarding the pattern name.<br><br>`Required` and `Unique` |
| Title | This field specifies the title of the new pattern.<br><br>`Required` and `Unique` |
| Pattern Logo | You can upload the pattern logo in this field. |

## Pattern Page
This page contains all the details of your pattern. From this page, You can manage the pattern schema, templates, model, and files.

### Overview Page
It is the first section displayed when you enter the project page. This page summarizes all the details regarding your project.

| Section | Description |
| ------ | ------ |
| Basic Info | This table shows the basic information about the pattern. See [**"General Settings Page"**](#general-settings-page) for further details. |
| Patterns | This section lists the base patterns of the pattern. See [**"Patterns Page"**](#patterns-page) for details. |
| Dosyalar | This section shows the static files of the pattern. See [**"Files Page"**](#files-page) for details. |
| Versions | This section lists the pattern versions. For details, see [**"Versions Page"**](#versions-page). |
| Members | This section lists the pattern members. See [**"Members Page"**] (#members-page) for details. |
| Activity Log | This section lists the updates that are performed on the pattern by the members. |

### Schema Page
Patterns require specific fields and parameters to be defined by the user when creating the model. This section determines what fields and parameters to be defined by the user. Additionally, using this section, you can define a way to retrieve these fields and parameters from the user.

| Section | Description |
| ------ | ------ |
| <i class="fas fa-history"></i> Commit History | When you update the schema, a copy of the schema is saved in the local memory of your browser. Using **"Commit History"**, you can revert a previous update. |
| <i class="fas fa-times-circle"></i> <i class="fas fa-exclamation-triangle"></i> <i class="fas fa-info-circle"></i> Validation Log | During the schema update process, a validation check is performed on whether the schema satisfies the validation conditions. Incompatible sections are marked and shown to the user. Pressing the **"Validation Log"** button displays the window listing all error, warning and information messages. |
| Search Field | Using this section, you can search fields and values. You can also enter search commands that include **Regular Expression**. |
| <i class="fas fa-minus-square"></i> Collapse All | Collapses all arrays in the schema content, so you can only expand fields, you want to edit. |
| <i class="fas fa-plus-square"></i> Expand All | You can click this link to expand all pre-collapsed arrays in the content. |
| <i class="fab fa-js-square"></i> Edit as JSON | You can click this link to edit the schema in JSON syntax. |

### Validation Page
Once the schema of the pattern is determined, it is necessary to specify the conditions applied to verify defined fields and parameters. In this way, you can guide users while they are creating their model based on your pattern. Also, you can make the necessary checks before the source code generation process. Error, warning, and information notes will be shown to users based on your conditions. Thus, you can provide a way for them to fix their invalid parameters and field values before the source code generation process.

| Section | Description |
| ------ | ------ |
| <i class="fas fa-history"></i> Commit History | When you update the validation model, a copy of the validation model is saved in the local memory of your browser. Using **"Commit History"**, you can revert a previous update. |
| <i class="fas fa-times-circle"></i> <i class="fas fa-exclamation-triangle"></i> <i class="fas fa-info-circle"></i> Validation Log | During the validation model update process, a validation check is performed on whether the model satisfies the validation conditions. Incompatible sections are marked and shown to the user. Pressing the **"Validation Log"** button displays the window listing all error, warning and information messages. |
| Search Field | Using this section, you can search fields and values. You can also enter search commands that include **Regular Expression**. |
| <i class="fas fa-minus-square"></i> Collapse All | Collapses all arrays in the validation model content, so you can only expand fields, you want to edit. |
| <i class="fas fa-plus-square"></i> Expand All | You can click this link to expand all pre-collapsed arrays in the content. |
| <i class="fab fa-js-square"></i> Edit as JSON | You can click this link to edit the validation model in JSON syntax. |

### Files Page
In the source code generation phase, some files need to be added directly, without making any modifications to their content. These files are called static files. Using this section, you can create required directories and upload static files.

The files that you can upload in this section can be binary (image, audio, compressed) files, and text-based files. You can edit text-based files with the help of an integrated editor. Additionally, you can upload all static files as a single compressed .zip file, and then you can uncompress.

### Templates Page
One of the most important components of a pattern is templates. The templates are the micro-generators attached to pattern schema. Pyronome combines and runs these micro-generators while generating source code, according to the content of the model.

| Section | Description |
| ------ | ------ |
| <i class="fas fa-history"></i> Commit History | When you update the template model, a copy of the template model is saved in the local memory of your browser. Using **"Commit History"**, you can revert a previous update. |
| <i class="fas fa-times-circle"></i> <i class="fas fa-exclamation-triangle"></i> <i class="fas fa-info-circle"></i> Validation Log | During the template model update process, a validation check is performed on whether the model satisfies the validation conditions. Incompatible sections are marked and shown to the user. Pressing the **"Validation Log"** button displays the window listing all error, warning and information messages. |
| <i class="fab fa-git-alt"></i> Repository | In some cases, it may be useful to store templates as files and update these files in a code repository. By clicking this button, you can specify a repository for the template files. |
| Pull & Compile! | If you specify a repository and it is enabled, click this button to pull and compile the template files. If a repository is not specified or not enabled, only compile operation is performed by clicking this button. |
| Search Field | Using this section, you can search fields and values. You can also enter search commands that include **Regular Expression**. |
| <i class="fas fa-minus-square"></i> Collapse All | Collapses all arrays in the template model content, so you can only expand fields, you want to edit. |
| <i class="fas fa-plus-square"></i> Expand All | You can click this link to expand all pre-collapsed arrays in the content. |
| <i class="fab fa-js-square"></i> Edit as JSON | You can click this link to edit the template model in JSON syntax. |
| <i class="fas fa-file-download"></i> Download | You can click this link to download the template files saved in the system. |

<div class="panelize-infobox infobox-warning">
    <p>
        <strong><i class="fas fa-exclamation-triangle"></i> Warning:</strong>
    </p>
    <p>If you have specified a repository and it is enabled, you can not modify the templates through the interface. All modification operations can be carried out via the repository.</p>
</div>

<div class="panelize-infobox infobox-info">
    <p>
        <strong><i class="fas fa-info-circle"></i> Note:</strong>
    </p>
    <p>Only the reading operation is done from the repository specified for the templates. No file is uploaded to the specified repository.</p>
</div>

You can press the **"<i class="fab fa-git-alt"></i> Repository"** button to specify a repository for the templates.

| Form Field | Description |
| ------ | ------ |
| Enabled | This field indicates whether the repository is enabled or not. Pull operation is not performed on disabled repositories. |
| Authenticate using HTTPS | This field specifies the method of authentication. If you check this option, authentication will be performed over HTTPS. |
| Authenticate using SSH | This field specifies the method of authentication. If you check this option, authentication will be performed over SSH. |
| E-mail Address | This field specifies the e-mail address of the user who has access to the repository. |
| User Name | This field specifies the user name of the user who has access to the repository. |
| HTTPS URL | This field is displayed when you check the **"Authenticate using HTTPS"** option. Specifies the HTTPS address.<br><br>`Required` |
| HTTPS Password | This field is displayed when you check the **"Authenticate using HTTPS"** option. Specifies the password will be used to connect over HTTPS. |
| SSH Host | This field is displayed when you check the **"Authenticate using SSH"**. Specifies the SSH address.<br><br>`Required` |
| Generate SSH Keypair | This field is displayed when you check the **"Authenticate using SSH"**. An SSH key pair is automatically generated each time you create a new repository over SSH authentication. You can select this option if you want to recreate the key pair for an existing repository. |
| Branch Name | This field specifies the branch name of the repository that will hold the generated source code. If the specified branch does not exist, pull operation could not be performed.<br><br>`Required` |
| Template Folder | This field indicates the template directory that holds template files. |
| Auto-pull before compile operation | The templates files are automatically pulled from the specified repository before each compile operation if you check this checkbox. If this checkbox is not checked, you should click **"Check & Compile!"** button each time you need to pull template files from the repository. |

### Variables Page
More than one pattern can be installed on a single project. The source code generation process for these patterns is performed separately. Also, source code generation can be performed by parallel processing. In some cases, you need to define global variables that are available entire source code generation process. In this case, with the help of this section, you can define global variables.

| Section | Description |
| ------ | ------ |
| <i class="fas fa-history"></i> Commit History | When you update the variables, a copy of this update is saved in the local memory of your browser. Using **"Commit History"**, you can revert a previous update. |
| <i class="fas fa-times-circle"></i> <i class="fas fa-exclamation-triangle"></i> <i class="fas fa-info-circle"></i> Validation Log | During the variable update process, a validation check is performed on whether the variables satisfy the validation conditions. Incompatible sections are marked and shown to the user. Pressing the **"Validation Log"** button displays the window listing all error, warning and information messages. |
| Search Field | Using this section, you can search fields and values. You can also enter search commands that include **Regular Expression**. |
| <i class="fas fa-minus-square"></i> Collapse All | Collapses all arrays in the content, so you can only expand fields, you want to edit. |
| <i class="fas fa-plus-square"></i> Expand All | You can click this link to expand all pre-collapsed arrays in the content. |
| <i class="fab fa-js-square"></i> Edit as JSON | You can click this link to edit the variables in JSON syntax. |

### Model Page
You can use this section to define a default model for the pattern.

| Section | Description |
| ------ | ------ |
| <i class="fas fa-history"></i> Commit History | When you update the model, a copy of the model is saved in the local memory of your browser. Using **"Commit History"**, you can revert a previous update. |
| <i class="fas fa-times-circle"></i> <i class="fas fa-exclamation-triangle"></i> <i class="fas fa-info-circle"></i> Validation Log | During the model update process, a validation check is performed on whether the model satisfies the conditions of the selected patterns. Incompatible sections are marked and shown to the user. Pressing the **"Validation Log"** button displays the window listing all error, warning and information messages. |
| Search Field | Using this section, you can search fields and values. You can also enter search commands that include **Regular Expression**. |
| <i class="fas fa-minus-square"></i> Collapse All | Collapses all arrays in the model content, so you can only expand fields, you want to edit. |
| <i class="fas fa-plus-square"></i> Expand All | You can click this link to expand all pre-collapsed arrays in the content. |
| <i class="fab fa-js-square"></i> Edit as JSON | You can click this link to edit the variables in JSON syntax. |

### Patterns Page
Just as in projects, you can install another pattern to your pattern. This approach eliminates the need to select some lower-level patterns over and over again.

By clicking the **"Install Pattern(s)"** button, you can open the **"Install Pattern(s)"** window showing the possible pattern options that you can install to your pattern. With the help of this section, you can search for patterns according to your criteria and install the desired pattern(s), also purchase paid ones.

The list of installed patterns is in the middle of the page. You can sort patterns with special sorting grips to the left of each line. Additionally, with the version selector at the right of each line in the list, you can choose a specific version and perform a source code generation process based on this selected version.

### General Settings Page
Using this page, you can update the general information of the pattern.

| Form Field | Description |
| ------ | ------ |
| Enabled | Using this field, you can specify whether the pattern is enabled or not. When you disable a pattern, other members cannot view this pattern. |
| Organization | This field specifies in which namespace that the new pattern will be created. This field lists your user name and the organizations you have added.<br><br>`Required` |
| Use Existing Directory | This field specifies that the new pattern will be created into an existing directory. |
| Create New Directory | When this field is selected, the new pattern is created in the new directory. |
| Main Directory | This field is displayed when the **"Create New Directory"** is selected. Specifies the main directory where the pattern will be created. |
| Sub Directory | This field is displayed when the **"Create New Directory"** is selected. Specifies the subdirectory where the pattern will be created. |
| Name | This field specifies the name of the pattern.<br><i class="fas fa-exclamation-triangle"></i> Please note the following criteria regarding the pattern name.<br><br>`Required` and `Unique` |
| Title | This field specifies the title of the pattern.<br><br>`Required` and `Unique` |
| Short Description | This field specifies a one-sentence description of the pattern. |
| Description | This field specifies the description of the pattern. |
| Visibility | This field specifies the visibility of the pattern. Patterns can be **"Public"** or **"Private"**. **"Public"** patterns can be displayed on the Marketplace. **"Private"** patterns can only be viewed by its members. |
| Pattern Logo | You can upload the pattern logo in this field. |

<div class="panelize-infobox infobox-warning">
    <p>
        <strong><i class="fas fa-exclamation-triangle"></i> Warning:</strong>
    </p>
    <p>Please consider the followings regarding your pattern name:
    <ul>
        <li>It must contain only English characters.</li>
        <li>It cannot contain spaces and tab characters.</li>
        <li>It must be at least three characters long.</li>
        <li>You can enter only the "-" and underscore "_" characters as punctuation.</li>
        <li>It cannot begin with number, the middle line "-" and the underscore "_".</li>
    </ul></p>
</div>

### Members Page
In this section, you can determine the users who will perform the viewing, editing, and managing operations on the pattern.

You can add 3 (three) different types of members to the patterns:
- Owner: This user has full authority over the pattern. Owner users can add other users.
- Developer: This user has permission to update the pattern properties, the model, and the patterns.
- Viewer: This user can display pattern properties, the model, and the patterns, but cannot modify them.

<div class="panelize-infobox infobox-info">
    <p>
        <strong><i class="fas fa-info-circle"></i> Note:</strong>
    </p>
    <p>The members you will add to the pattern must be registered to the platform. You can invite not registered users by specifying their e-mail address.</p>
</div>

### Versions Page
You can use this section to create copies of the pattern with different versions. When determining pattern versions,

1. Major
2. Minor
3. Patch

version numbers must be specified.

In addition, you can label pre-release versions by adding the following suffixes:

- `dev`
- `alpha`
- `beta`

<div class="panelize-infobox infobox-info">
    <p>
        <strong><i class="fas fa-info-circle"></i> Note:</strong>
    </p>
    <p>Pyronome recommends the <strong>Semantic Versioning</strong> approach to identifying versions. For more information on Semantic Versioning, please visit <a href="https://semver.org/lang/en/"> https://semver.org/</a>.</p>
</div>

### Marketplace Page
Using this section, you can update the information about the Marketplace page of the pattern. Most of the form fields in this section can also be updated using the **"General Settings Page"** section.

| Form Field | Description |
| ------ | ------ |
| Title | This field specifies the title of the pattern.<br><br>`Required` and `Unique` |
| Short Description | This field specifies a one-sentence description of the pattern.<br><br>`Required` |
| Category | This field specifies the category under which the pattern will be listed.<br><br>`Required` |
| List as Project Template | When you select this option, the pattern is listed as a project application template on the new project page. |
| Description | This field specifies the description of the pattern. |
| Keywords | Keywords that will be used when any search is performed on the Marketplace.<br><br>`Required` |
| Web URL | This field specifies the web URL of the pattern. |
| Support URL | This field specifies the support address available to the pattern users. You can enter GitHub, GitLab, BitBucket, etc. **"Issues"** page addresses of the pattern repository to this field. |
| Repository URL | This field specifies the repository URL of the pattern. |
| README.md URL (README Tab) | **"README"** tab shows the content of the README.md file entered to this field on the Marketplace pattern page. |
| Licensing | This field specifies the usage terms and license of the pattern. |
| Pricing | This field specifies the pricing strategy of the pattern. |
| Free | You should check this option for providing your pattern for free. |
| Fixed Price | You should check this option to specify a fixed price for the pattern. |
| Bundle Pricing | You should check this option to combine multiple patterns and specify a single price. |
| Price Per User (USD)  | This field is displayed when **"Fixed Price"** is selected. Two different pricing models are applied for patterns: **"Price Per User"** and **"Price Per Project"**. **"Price Per Project"** pricing indicates the usage price of the pattern in only one project; **"Price Per User"** pricing indicates the usage price in all projects and user patterns. **"Price Per Project"** price is suggested to be one-fifth of the **"Price Per User"**. |
| Enable Price Per Project | This field is displayed when **"Fixed Price"** is selected. You should check this option if you would like to provide **"Price Per Project"** pricing in addition to **"Price Per User"** for the pattern. |
| Price Per Project (USD) | This field is displayed when **"Enable Price Per Project"** is selected. You can specify **"Price Per Project"** using this field. |
| Discount on Price Per User | This field is displayed when **"Bundle Pricing"** is selected. You can specify the discount to be applied to the bundled patterns' **"Price Per User"** total price. You can enter a percentage or an exact amount in this field. |
| Enable Discount on Price Per Project | This field is displayed when **"Bundle Pricing"** is selected. You can specify **"Price Per Project"** discounts for the bundled pattern by selecting this option. |
| Discount on Price Per Project | This field is displayed when **"Enable Discount on Price Per Project"** is selected. You can specify the discount to be applied to the bundled patterns' **"Price Per Project"** total price. You can enter a percentage or an exact amount in this field. |
| Discount | This field is displayed when **"Fixed Price"** or **"Bundle Pricing"** is selected. You can specify the discount to be applied to the pattern using this field. |
| Enable Discount | This field is displayed when **"Fixed Price"** or **"Bundle Pricing"** is selected. You can check this option to specify the discount to be applied to the pattern. |
| Enable Discount on Price Per User (Discount Section) | This field is displayed when **"Enable Discount"** is selected. You can check this option to specify the discount to be applied on **"Price Per User"**. |
| Enable Discount on Price Per Project (Discount Section) | This field is displayed when **"Enable Discount"** is selected. You can check this option to specify the discount to be applied on **"Price Per Project"**. |
| Discount on Price Per User (Discount Section) | This field is displayed when **"Enable Discount on Price Per User"** in Discount Section is selected. You can specify the discount to be applied to the pattern **"Price Per User"** price. You can enter a percentage or an exact amount in this field. |
| Discount on Price Per Project (Discount Section) | This field is displayed when **"Enable Discount on Price Per Project"** in Discount Section is selected. You can specify the discount to be applied to the pattern **"Price Per Project"** price. You can enter a percentage or an exact amount in this field. |
| Image Gallery | You can upload up to 10 some images, screenshots, etc. of the pattern in this section. The first image will be considered as a featured image. |
| First Name | This field specifies the first name of the pattern developer. |
| Last Name | This field specifies the last name of the pattern developer. |
| Phone Number | This field specifies the phone number of the pattern developer. |
| E-mail Address | This field specifies the e-mail address of the pattern developer. |
| Notes | You can enter some notes about the developer's contact information. |

<div class="panelize-infobox infobox-warning">
    <p>
        <strong><i class="fas fa-exclamation-triangle"></i> Warning:</strong>
    </p>
    <p>The URL addresses specified in this section must be publicly accessible.</p>
</div>