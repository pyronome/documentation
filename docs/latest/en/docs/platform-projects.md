---
id: platform-projects
title: Projects
---

<a id="aHeaderMenuAnchor" data-header-menu="Docs"></a>

This section contains projects that you are developing on the platform.

## Projects Page
This page contains the projects you have created or are a member of. You can add new projects or view your existing projects on this page.

| Table Field | Description |
| ------ | ------ |
| Name | This field shows the project title, the folder where the project is located and the project name. |
| Active Version | Pyronome allows users to create different versions of their projects. This field refers to the version in which the user actively makes modifications to it. The active version can be changed via the **"Versions"** page of the project. |
| Enabled | This field indicates whether the project is enabled or not. Other members cannot view disabled projects. |
| <i class="fas fa-users"></i> Members Button | Displays the **"Members"** page, which lists other members authorized to take action on the project. |
| <i class="fas fa-trash-alt"></i> Delete Button | You can use this button to delete a specific project. |

## New Project Page
This page contains the form, which you can add a new project.

| Form Field | Description |
| ------ | ------ |
| Enabled | This field indicates whether the project is enabled or not. Other members cannot view disabled projects. |
| Create Empty Project | When this field is selected, an empty project is created. |
| Clone Existing Project | You can create a new project by cloning a project that you have already created or have permission to edit. When this field is selected, you must choose a project. |
| Projects | This field is only displayed when the **"Clone Existing Project"** field is selected. This field specifies the main project that the new project will be cloned. This field lists the projects that you have previously created, or you have permission to edit. |
| Organization | This field specifies in which namespace that the new project will be created. This field lists your user name and the organizations you have added.<br><br>`Required` |
| Use Existing Directory | This field specifies that the new project will be created into an existing directory. |
| Create New Directory | When this field is selected, the new project is created in the new directory. |
| Main Directory | This field is displayed when the **"Create New Directory"** is selected. Specifies the main directory where the project will be created. |
| Sub Directory | This field is displayed when the **"Create New Directory"** is selected. Specifies the subdirectory where the project will be created. |
| Name | This field specifies the name of the new project.<br><i class="fas fa-exclamation-triangle"></i> Please note the criteria in the [General Settings Page](#general-settings-page) section regarding the project name.<br><br>`Required` and `Unique` |
| Title | This field specifies the title of the new project.<br><br>`Required` |
| Project Logo | You can upload the project logo in this field. |

## Project Page
This page contains all the details of your project. From this page, you can manage the project model, source code, and server settings.

### Overview Page
It is the first section displayed when you enter the project page. This page summarizes all the details regarding your project.

| Section | Description |
| ------ | ------ |
| Basic Info | This table shows the basic information about the project. See [**"General Settings Page"**](#general-settings-page) for further details. |
| Patterns | This section lists the patterns of the project. See [**"Patterns Page"**](#patterns-page) for details. |
| Source Code | This section shows the generated source code of the project. See [**"Source Code Page"**](#source-code-page) for details. |
| Versions | This section lists the project versions. For details, see [**"Versions Page"**](#versions-page). |
| Members | This section lists the project members. See [**"Members Page"**] (#members-page) for details. |
| Activity Log | This section lists the updates that are performed on the project by the members. |
| Servers | This section lists the project servers are listed. See [**"Servers Page"**](#servers-page) for details. |
| Repositories | This section lists the project repositories. See [**"Repositories Page"**](#repositories-page) for details. |
| Webhooks | This section lists the webhooks of the project. See [**"Webhooks Page"**](#webhooks-page) for details. |

### Model Page
In this section, you can model your project based on selected patterns.

| Section | Description |
| ------ | ------ |
| <i class="fas fa-history"></i> Commit History | When you update the model, a copy of the model is saved in the local memory of your browser. Using **"Commit History"**, you can revert a previous update. |
| <i class="fas fa-times-circle"></i> <i class="fas fa-exclamation-triangle"></i> <i class="fas fa-info-circle"></i> Validation Log | During the model update process, a validation check is performed on whether the model satisfies the conditions of the selected patterns. Incompatible sections are marked and shown to the user. Pressing the **"Validation Log"** button displays the window listing all error, warning and information messages. |
| Search Field | Using this section, you can search the model fields and values. You can also enter search commands that include **Regular Expression**. |
| <i class="fas fa-minus-square"></i> Collapse All | Collapses all arrays in the model content, so you can only expand fields, you want to edit. |
| <i class="fas fa-plus-square"></i> Expand All | You can click this link to expand all pre-collapsed arrays in the content. |
| <i class="fab fa-js-square"></i> Edit as JSON | You can click this link to edit the model in JSON syntax. |

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

### Patterns Page
The patterns in a project are enabling the source code generation. You can install multiple patterns in a single project. In this way, the patterns can easily take care of the source code generation of different parts on an application. You can change an application's backend/frontend technology by changing just the pattern(s) dealing with the backend. In the same way, you can update an application's backend/frontend framework into a new version.

By clicking the **"Install Pattern(s)"** button, you can open the **"Install Pattern(s)"** window showing the possible pattern options that you can install to your project. With the help of this section, you can search for patterns according to your criteria and install the desired pattern(s), also purchase paid ones.

The list of installed patterns is in the middle of the page. You can sort patterns with special sorting grips to the left of each line. Additionally, with the version selector at the right of each line in the list, you can choose a specific version and perform a source code generation process based on this selected version.

### Source Code Page
You can view the source code of your project from this page. If you make any changes in the model or patterns, the source code generation process is started immediately after opening this page.

You can press **"Generate Now!"** to manually restart the source code generation process. After you restart the source code generation process, the page reloads. The source code generation process may continue in the background. **"Generating ..."** is displayed at the top right of the page while the source code generation is in progress. When the source code generation process is complete, the file list is automatically updated. The source code generation process may vary depending on the size of the project and the content of the selected patterns.

You can press the **"Download (.zip)"** button to download the generated source code as a single .zip file.

You can view the source code -the list of files and directories- in the middle of the page. When you click on any directory, you can see the contents of that directory. Similarly, when you click on any file, you can view its contents if the file is text-based.

### General Settings Page
Using this page, you can update the general information of the project.

| Form Field | Description |
| ------ | ------ |
| Enabled | This field indicates whether the project is enabled or not. Other members cannot view disabled projects. |
| Organization | This field specifies in which namespace that the project will be located. This field lists your user name and the organizations you have added.<br><br>`Required` |
| Use Existing Directory | This field specifies that the project will be located into an existing directory. |
| Create New Directory | When this field is selected, the project is located in the new directory. |
| Main Directory | This field is displayed when the **"Create New Directory"** is selected. Specifies the main directory where the project will be located. |
| Sub Directory | This field is displayed when the **"Create New Directory"** is selected. Specifies the subdirectory where the project will be located. |
| Name | This field specifies the name of the project.<br><i class="fas fa-exclamation-triangle"></i> Please note the following criteria regarding the project name.<br><br>`Required` and `Unique` |
| Title | This field specifies the title of the project.<br><br>`Required` and `Unique` |
| Description | This field specifies the description of the project. |
| Project Logo | You can upload the project logo in this field. |

<div class="panelize-infobox infobox-warning">
    <p>
        <strong><i class="fas fa-exclamation-triangle"></i> Warning:</strong>
    </p>
    <p>Please consider the followings regarding your project name:
    <ul>
        <li>It must contain only English characters.</li>
        <li>It cannot contain spaces and tab characters.</li>
        <li>It must be at least three characters long.</li>
        <li>You can enter only the "-" and underscore "_" characters as punctuation.</li>
        <li>It cannot begin with number, the middle line "-" and the underscore "_".</li>
    </ul></p>
</div>

### Members Page
In this section, you can determine the users who will perform the viewing, editing, and managing operations on the project.

You can add 3 (three) different types of members to the project:
- Owner: This user has full authority over the project. Owner users can add other users.
- Developer: This user has permission to update the project properties, the model, and the patterns.
- Viewer: This user can display project properties, the model, and the patterns, but cannot modify them.

<div class="panelize-infobox infobox-info">
    <p>
        <strong><i class="fas fa-info-circle"></i> Note:</strong>
    </p>
    <p>The members you will add to the project must be registered to the platform. You can invite not registered users by specifying their e-mail address.</p>
</div>

### Versions Page
You can use this section to create copies of the project model with different versions. When determining project versions,

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

### Servers Page
You can use this section to specify the servers that will be installed after the source code generation process.

In this section, you can add the following servers:

- FTP Server
- SFTP Server

You can press the **"Deploy Now!"** button to manually upload the generated source code to the existing servers. The source code will be uploaded to the servers in the order you specify.

<div class="panelize-infobox infobox-warning">
    <p>
        <strong><i class="fas fa-exclamation-triangle"></i> Warning:</strong>
    </p>
    <p>The installation of source code to the servers is performed consecutively. In other words, the installation to the second server does not start until the installation to the first server is complete.</p>
</div>

You can press **"New Server"** button to add a new server.

| Form Field | Description |
| ------ | ------ |
| Enabled | This field indicates whether the server is enabled or not. Deployment is not performed on disabled servers. |
| Type | This field specifies the type of the server. Currently, you can choose FTP or SFTP server.<br><br>`Required` |
| Name | This field specifies the name of the server.<br><i class="fas fa-exclamation-triangle"></i> Please note the following criteria regarding the server name.<br><br>`Required` and `Unique` |
| Description | This field specifies the description of the server. |
| Host | You can specify the server address in this field.<br><br>`Required` |
| User | You can enter the authorized user name to access the server.<br><br>`Required` |
| Password | You can enter the authorized user password to access the server.<br><br>`Required` |
| Home Folder | You can specify the directory in which the installation will be performed after the connection is established using this field. |
| Port | You can specify the port where the connection will be established.<br><br>`Required` and `Varsayılan Değer: 21` |

<div class="panelize-infobox infobox-warning">
    <p>
        <strong><i class="fas fa-exclamation-triangle"></i> Warning:</strong>
    </p>
    <p>Please consider the followings regarding your server name:
    <ul>
        <li>It must contain only English characters.</li>
        <li>It cannot contain spaces and tab characters.</li>
        <li>It must be at least three characters long.</li>
        <li>You can enter only the "-" and underscore "_" characters as punctuation.</li>
        <li>It cannot begin with number, the middle line "-" and the underscore "_".</li>
    </ul></p>
</div>

To view transaction logs for any server, you can press <strong><i class = "fas fa-file-alt"></i></strong> on the right-hand side of that record line.

Once you have entered all connection parameters, you can press **"TEST"** to test the connection.

### Repositories Page
You can use this section to define the repositories where the source code will automatically upload after the source code generation process.

You can press the **"Push Now!"** button to manually push the generated source code into the existing repositories. The source code will be uploaded into the repositories in the order you specify.

<div class="panelize-infobox infobox-warning">
    <p>
        <strong><i class="fas fa-exclamation-triangle"></i> Warning:</strong>
    </p>
    <p>The uploading of source code to the repositories is performed consecutively. In other words, the upload process to the second repository does not start until the upload process to the first repository is complete.</p>
</div>

You can press the **"New Repository"** button to add a new repository.

| Form Field | Description |
| ------ | ------ |
| Enabled | This field indicates whether the repository is enabled or not. Push operation is not performed on disabled repositories. |
| Repository Name | This field specifies the name of the repository.<br><br>`Required` |
| Branch Name | This field specifies the branch name of the repository that will hold the generated source code. If the specified branch does not exist, firstly, the branch is created, and then the source code uploaded.<br><br>`Required` |
| Main Directory | If the generated code must be loaded into a particular subdirectory within a specific branch, you can specify the name of the directory in this field. |
| Delete All Files Before Adding Generated Files | When you check this option, the target directory contents will be deleted before the upload process. This feature makes it possible to remove related files that are renamed and deleted from the project model. |
| E-mail Address | This field specifies the e-mail address of the user who has access to the repository. In this way, you can easily distinguish which user performed the uploading process.<br><br>`Required` |
| User Name | This field specifies the user name of the user who has access to the repository. |
| Authenticate using HTTPS | This field specifies the method of authentication. If you check this option, authentication will be performed over HTTPS. |
| Authenticate using SSH | This field specifies the method of authentication. If you check this option, authentication will be performed over SSH. |
| HTTPS URL | This field is displayed when you check the **"Authenticate using HTTPS"** option. Specifies the HTTPS address.<br><br>`Required` |
| HTTPS Password | This field is displayed when you check the **"Authenticate using HTTPS"** option. Specifies the password will be used to connect over HTTPS.<br><br>`Required` |
| SSH Host | This field is displayed when you check the **"Authenticate using SSH"**. Specifies the SSH address.<br><br>`Required` |
| Generate SSH Keypair | This field is displayed when you check the **"Authenticate using SSH"**. An SSH key pair is automatically generated each time you create a new repository over SSH authentication. You can select this option if you want to recreate the key pair for an existing repository. |
| Commit Message | This field specifies the commit message to display in the repository logs. In this field, you can enter mustache templates like `{{project_name}}`, `{{project_title}}`, etc. You can find a complete list of these mustache templates below.<br><br>`Required` |

To view upload process logs for any repository, you can press the <strong><i class="fas fa-file-alt"></i></strong> icon to the right of the corresponding record row.

#### Commit Message Mustache Templates
Commit messages contains brief information about a particular commit performed on a repository. Pyronome provides a practical way of uploading generated source code to your repositories. But, it is still essential to have descriptive commit messages. You can add some special identifiers to make your commit messages more descriptive.

Default commit message:

```HTML
Code generation auto-push by Pyronome
```

Commit message with mustache templates:

```HTML
Code generation auto-push by Pyronome for {{project_title}} ({{project_name}}, {{project_active_version}}).
```

Below is a list of specific identifiers that can be used in the commit messages:

| Identifier | Description |
| ------ | ------ |
| `{{current_date}}` | This identifier holds the current date, based on user timezone. E.g. `20200516` |
| `{{current_datetime}}` | This identifier holds the current date and time, based on user timezone. E.g. `20200516235959` |
| `{{current_datetime_formatted}}` | This identifier holds the formatted current date and time, based on user language settings. E.g. `16.05.2020 23:59` |
| `{{current_day}}` | This identifier holds the current day as integer, based on user timezone. E.g. `16` |
| `{{current_hour}}` | This identifier holds the current hour as integer, based on user timezone. E.g. `23` |
| `{{current_minute}}` | This identifier holds the current minute as integer, based on user timezone. E.g. `59` |
| `{{current_month}}` | This identifier holds the current month as integer, based on user timezone. E.g. `05` |
| `{{current_time}}` | This identifier holds the current time, based on user timezone. E.g. `235959` |
| `{{current_year}}` | This identifier holds the current year as 4-digit integer, based on user timezone. E.g. `2020` |
| `{{project_active_version}}` | This identifier holds the active version of the project. |
| `{{project_guid}}` | This identifier holds the global unique id of the project. This identifier, unlike `{{project_id}}`, is unique to each element within the platform. |
| `{{project_id}}` | This identifier holds the unique integer id of the project. |
| `{{project_main_directory}}` | This identifier holds the main directory of the project. |
| `{{project_name}}` | This identifier holds the name of the project. |
| `{{project_path}}` | This identifier holds the namespace of the project. |
| `{{project_short_description}}` | This identifier holds the short description of the project. |
| `{{project_sub_directory}}` | This identifier holds the subdirectory of the project. |
| `{{project_title}}` | This identifier holds the title of the project. |
| `{{server_host}}` | This identifier holds the address of the server where the repository is located. |
| `{{server_name}}` | This identifier holds the name of the server where the repository is located. |
| `{{user_full_name}}` | This identifier holds the full name of the user. |
| `{{user_guid}}` | This identifier holds the global unique id of the user. |
| `{{user_id}}` | This identifier holds the unique integer id of the user. |
| `{{user_name}}` | This identifier holds the name of the user. |

### Webhooks Page
You can automate your software development processes by creating webhooks attached to the source code generation, server deployment, and repository push events.

<div class="panelize-infobox infobox-warning">
    <p>
        <strong><i class="fas fa-exclamation-triangle"></i> Warning:</strong>
    </p>
    <p>The webhook requests are posted consecutively. In other words, the second webhook request does not post until the first webhook request is posted.</p>
</div>

You can press **"New Webhook"** button to add a new webhook.

| Form Field | Description |
| ------ | ------ |
| Enabled | This field indicates whether the webhook is enabled or not. The request is not posted to disabled webhooks. |
| Name | This field specifies the name of the webhook. <br><br>`Required` |
| URL | This field specifies the URL address of the request.<br><br>`Required` |
| Secret Key | You can specify a secret key to verify that a specific web request is posted from Pyronome servers. |
| On Generate Event | If you check this option, the web request is posted after the code generation process. |
| On Deploy Event | If you check this option, the web request is posted after the deploy process. |
| On Push Event | If you check this option, the web request is posted after the push process. |

To view the logs for any webhook, you can press <strong><i class="fas fa-file-alt"></i></strong> icon to the right of the corresponding record row.

Below is a sample webhook request.

```JSON
{
	"event": {
		"guid": "E0X0A0M0L0E0G0U0I0D",
		"name": "Example1",
		"type": 1
	},
	"server": {
		"host":"www.pyronome.com",
		"name":"platform"
	},
	"webhook": {
		"id": 1,
		"guid": "E0X0A0M0L0E0W0B0H0O0O0K",
		"index": "1",
		"name": "ExampleWebhook1",
		"url": "https://example.com",
		"secret_token": "YOUR_SECRET_TOKEN",
        "on_generate": 1,
        "on_deploy": 0,
        "on_push": 0
	},
	"project": {
		"id": 1,
		"guid": "E0X0A0M0L0E0P0R0J0E0C0T",
		"name": "exampleproject1",
		"title": "Example Project 1",
		"short_description": "Project Short Description",
        "active_version": "1.0.0",
        "path": "exampleuser/exampleproject1",
        "main_directory": "",
        "sub_directory": ""
	},
	"user": {
		"id": 1,
		"guid": "E0X0A0M0L0E0U0S0E0R",
		"user_name": "exampleuser",
        "full_name": "Example User"
	}
}
```