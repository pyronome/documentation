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
| Basic Info | This table shows the basic information about the project. See [**"General Settings Page"**](# general-settings-page) for further details. |
| Patterns | This section lists the patterns of the project. See [**"Patterns Page"**](#patterns-page) for details. |
| Source Code | This section shows the generated source code of the project. See [**"Source Code Page"**](#source-code-page) for details. |
| Versions | This section lists the project versions. For details, see [**"Versions Page"**](#versions-page). |
| Members | This section lists the project members. See [**"Members Page"**] (#members-page) for details. |
| Activity Log | This section lists the updates that are performed on the project by the users. |
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
        <li>It must be longer than two characters.</li>
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
        <li>It must be longer than two characters.</li>
        <li>You can enter only the "-" and underscore "_" characters as punctuation.</li>
        <li>It cannot begin with number, the middle line "-" and the underscore "_".</li>
    </ul></p>
</div>

To view transaction logs for any server, you can press <strong><i class = "fas fa-file-alt"></i></strong> on the right-hand side of that record line.

Once you have entered all connection parameters, you can press **"TEST"** to test the connection.

### Repositories Page
Projenin kaynak kod üretim işleminden sonra otomatik olarak dosyaların yükleneceği kod depolarını belirtmek için bu bölümü kullanabilirsiniz.

Oluşturulan kaynak kodu elle mevcut kod depolarına yüklemek için **"Şimdi İttir!"** düğmesine basabilirsiniz. Kaynak kod belirlediğiniz sıra ile kod depolarına yüklenecektir.

<div class="panelize-infobox infobox-warning">
    <p>
        <strong><i class="fas fa-exclamation-triangle"></i> Warning:</strong>
    </p>
    <p>Kod depolarına kaynak kod yükleme işlemi ardışık olarak gerçekleştirilmektedir. Başka bir deyişle, ilk kod deposuna yükleme işlemi tamamlanmadan ikinci kod deposuna yükleme işlemi başlatılmaz.</p>
</div>

Yükleme işleminin yapılacağı yeni bir kod deposu kaydı eklemek için **"Yeni Kod Deposu"** düğmesine basabilirsiniz.

| Form Field | Description |
| ------ | ------ |
| Enabled | This field indicates whether the repository is enabled or not. Push operation is not performed on disabled repositories. |
| Kod Deposu Adı | Kod depolarını listede ayırt etmek için bir isim verilmesi gerekmektedir. <br><br>`Required` |
| Dal Adı (Branch) | Üretilen kodun hangi dala (branch) yükleneceğini belirten alandır. Eğer kod deposunda belirtilen dal bulunmuyorsa, dal önce üretilir daha sonra kod yükleme işlemi yapılır.<br><br>`Required` |
| Main Directory | Üretilen kod, kod deposu içindeki belli bir dalın içinde özel bir alt dizine yüklenmesi gerekiyorsa bu alana yükleme yapılacak dizinin adının girilmesi gerekmektedir. |
| Dosyaları Eklemeden Önce Dizindeki Mevcut Dosyaları Sil | Bu seçenek işaretlendiğinde yükleme yapılmadan önce, yükleme yapılacak dizin içeriği silinir. Böylelikle model üzerinde adı değiştirilen ya da kaldırılan elemanlara ilişkin kodlar kolaylıkla temizlenebilir. |
| E-posta Adresi | Kod deposuna erişim yetkisi olan kullanıcının e-posta adresini belirtmektedir. Böylelikle kayıtlarda yükleme işleminin hangi kullanıcı tarafından yapıldığını kolaylıkla ayırt edebilirsiniz.<br><br>`Required` |
| Kullanıcı Adı | Kod deposuna erişim yetkisi olan kullanıcının kullanıcı adını belirtmektedir. |
| HTTPS Kullanarak Kimlik Doğrulama | Kimlik doğrulama işleminin hangi metotla yapılacağını belirten alandır. Bu alan işaretlenirse HTTPS üzerinden kimlik doğrulaması yapılacaktır. |
| SSH Kullanarak Kimlik Doğrulama | Kimlik doğrulama işleminin hangi metotla yapılacağını belirten alandır. Bu alan işaretlenirse SSH üzerinden kimlik doğrulaması yapılacaktır. |
| HTTPS URL | **"HTTPS Kullanarak Kimlik Doğrulama"** seçeneği işaretlendiğinde gösterilmektedir. HTTPS bağlantısı yapılacak adresi belirtir.<br><br>`Required` |
| HTTPS Password | **"HTTPS Kullanarak Kimlik Doğrulama"** seçeneği işaretlendiğinde gösterilmektedir. HTTPS bağlantısı yaparken kullanılacak şifreyi belirtir.<br><br>`Required` |
| SSH Adresi | **"SSH Kullanarak Kimlik Doğrulama"** seçeneği işaretlendiğinde gösterilmektedir. SSH bağlantısı yapılacak adresi belirtir.<br><br>`Required` |
| SSH Doğrulama Anahtar Çiftini Üret | **"SSH Kullanarak Kimlik Doğrulama"** seçeneği işaretlendiğinde gösterilmektedir. Her yeni SSH kimlik doğrulaması yapacak kod deposu kaydı eklendiğinde otomatik olarak SSH anahtar çifti oluşturulur. Mevcut bir kod deposu için anahtar çiftini tekrar üretmek isterseniz bu seçeneği işaretleyebilirsiniz. |
| İşlem Notu | Kod yükleme işleminin kod deposu kayıtlarında gösterilecek işlem notunu belirtir. İşlem notu bölümünde `{{project_name}}`, `{{project_title}}`, vb. özel tanımlayıcılar kullanabilirsiniz. Bu özel tanımların tam listesi aşağıda verilmiştir.<br><br>`Required` |

Herhangi bir kod deposuna ait işlem kayıtlarını görüntülemek için, ilgili kayıt satırının sağ tarafında bulunan <strong><i class="fas fa-file-alt"></i></strong> simgesine basabilirsiniz.

#### Commit Message Mustache Templates
Kod deposuna kod yükleme işlemi yapıldığında işlem kayıtları oluşturulur. Bu işlem kayıtları için kod yükleme işlemini yapan kullanıcılar özel notlar/mesajlar belirtebilmektedir. Pyronome üzerinden yapılan kod yükleme işlemlerine de benzer şekilde özel notlar/mesajlar eklenebilir. Eklenen bu mesajların içinde proje ve kod yükleme işlemine ait özel tanımlayıcılar kullanılabilir.

Varsayılan işlem notu:

```HTML
Code generation auto-push by Pyronome
```

Özel tanımlayıcı eklenmiş işlem notu:

```HTML
Code generation auto-push by Pyronome for {{project_title}} ({{project_name}}, {{project_active_version}}).
```

Aşağıda işlem notunda kullanılabilecek özel tanımlayıcıların listesini bulabilirsiniz:

| Tanımlayıcı | Description |
| ------ | ------ |
| `{{server_host}}` | Kod deposunun bulunduğu sunucunun adresini belirtir. |
| `{{server_name}}` | Kod deposunun bulunduğu sunucunun adını belirtir. |
| `{{project_id}}` | Kod yükleme işlemi yapılan projeye ait tamsayı tekil tanımlayıcıdır. |
| `{{project_guid}}` | Kod yükleme işlemi yapılan projeye ait rakam ve harflerden oluşan tekil tanımlayıcıdır. Bu tanımlayıcı `{{project_id}}` aksine, platform içinde her eleman için benzersiz olma niteliğine sahiptir. |
| `{{project_name}}` | Projenin adını belirtir. |
| `{{project_title}}` | Projenin başlığını belirtir. |
| `{{project_short_description}}` | Projenin kısa Descriptionsını belirtir. |
| `{{project_active_version}}` | Projenin etkin sürümünü belirtir. |
| `{{project_path}}` | Projenin ad uzayını belirtir. |
| `{{project_main_directory}}` | Projenin ana dizin adını belirtir. |
| `{{project_sub_directory}}` | Projenin alt dizin adını belirtir. |
| `{{user_id}}` | Kod yükleme işlemini yapan Pyronome kullanıcısına ait tamsayı tekil tanımlayıcıdır. |
| `{{user_guid}}` | Kod yükleme işlemini yapan Pyronome kullanıcısına ait rakam ve harflerden oluşan benzersiz tekil tanımlayıcıdır. |
| `{{user_name}}` | Kod yükleme işlemini yapan Pyronome kullanıcısına ait kullanıcı adını belirtir. |
| `{{user_full_name}}` | Kod yükleme işlemini yapan Pyronome kullanıcısına ait tam adı belirtir. |

### Webhooks Page
Projenin kaynak kod üretim, sunucu konuşlandırma ve kod depolarına ittirme işlemlerinden sonra web istekleri yapılmasını sağlayarak yazılım geliştirme süreçlerinizi otomatikleştirebilirsiniz.

<div class="panelize-infobox infobox-warning">
    <p>
        <strong><i class="fas fa-exclamation-triangle"></i> Warning:</strong>
    </p>
    <p>Web istekleri ardışık olarak gönderilmektedir. Başka bir deyişle, ilk web isteği gönderme işlemi tamamlanmadan ikinci istek gönderimi başlatılmaz.</p>
</div>

Yükleme işleminin yapılacağı yeni bir web isteği kaydı eklemek için **"Yeni Web İsteği"** düğmesine basabilirsiniz.

| Form Field | Description |
| ------ | ------ |
| Enabled | This field indicates whether the webhook is enabled or not. The request is not sent to disabled webhooks. |
| Name | Web isteğini listede ayırt etmek için bir isim verilmesi gerekmektedir. <br><br>`Required` |
| URL | Web isteğinin yapılacağı adresi belirtir.<br><br>`Required` |
| Gizli Anahtar | Web isteğinin Pyronome sunucuları tarafından gönderildiğini doğrulamak amacıyla gizli anahtar belirtebilirsiniz. |
| Üretme Olayı | Web isteğinin kod üretme işleminden sonra gönderilip/gönderilmeyeceğini belirleyen alandır. |
| Konuşlandırma Olayı | Web isteğinin sunucu konuşlandırma işleminden sonra gönderilip/gönderilmeyeceğini belirleyen alandır. |
| İttirme Olayı | Web isteğinin kod deposu ittirme işleminden sonra gönderilip/gönderilmeyeceğini belirleyen alandır. |

Herhangi bir web isteğine ait işlem kayıtlarını görüntülemek için, ilgili kayıt satırının sağ tarafında bulunan <strong><i class="fas fa-file-alt"></i></strong> simgesine basabilirsiniz.

Aşağıda örnek bir web isteğini görebilirsiniz.

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