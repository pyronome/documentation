---
id: platform-release-notes
title: Platform Release Notes
sidebar_label: Release Notes
---

<a id="aHeaderMenuAnchor" data-header-menu="Docs"></a>

## Version 3.1.8

1. Some improvements are made on the user interface for better usability.
2. Some styling updates are made on the user interface for better visuality.
3. Patches applied for some parts that are not working correctly.

## Version 3.1.7

1. Some improvements are made on the user interface for better usability.
2. Some styling updates are made on the user interface for better visuality.
3. Patches applied for some parts that are not working correctly.

## Version 3.1.6

1. Incoming Webhooks feature added. The incoming Webhooks feature enables automatic pattern compile and project code generation through webhooks from online repository services like GitHub, BitBucket, GitLab, etc.
2. Some improvements are made on the user interface for better usability.
3. Some styling updates are made on the user interface for better visuality.
4. Patches applied for some parts that are not working correctly.

## Version 3.1.5

1. Some improvements are made on the user interface for better usability.
2. Some styling updates are made on the user interface for better visuality.
3. Patches applied for some parts that are not working correctly.

## Version 3.1.4

1. Necessary updates were made for GDPR compliance.
2. "Private/Public" version visibility feature added for patterns.
3. The functionality of the file manager has been increased. File search features have been improved.
4. "Live Preview..." and "Browse Files..." marketplace buttons for patterns have been added.
5. Some improvements are made on the user interface for better usability.
6. Some styling updates are made on the user interface for better visuality.
7. Patches applied for some parts that are not working correctly.

## Version 3.1.3

1. The "Badges" section has been added to the "Marketplace" section under the "Settings" section of the patterns.
2. The "Variables" section has been added to the project page as in the pattern pages. Thus, database password, SSH key, access key, environment variables, etc. can also be defined within the project.
3. `skip_whitespace` feature has been added for pattern templates. With this feature's help, if a template contains only whitespace characters, this template can be skipped without taking action.
4. Some improvements are made on the user interface for better usability.
5. Some styling updates are made on the user interface for better visuality.
6. Patches applied for some parts that are not working correctly.

## Version 3.1.2

1. A more efficient directory structure was introduced for Snippet Injection.
2. The helper files `__glue__`, `__header__`, `__footer__` and `__default__` have been added for Snippet Injection. (See [`snippets` Directory Structure](/latest/en/docs/reference-snippet-injection/#snippets-directory-structure))
3. The timezone feature has been added to user profile settings.
4. The batch download feature has been added for pattern template files.
5. `skip_empty` and` remove_whitespace` features are added for pattern templates. Thus, while generating source code, empty templates can be skipped, or whitespace in the templates can be removed.
6. Detailed pricing options have been added to the "Marketplace" section under the "Settings" section for the patterns.
7. Some improvements are made on the user interface for better usability.
8. Some styling updates are made on the user interface for better visuality.
9. Patches applied for some parts that are not working correctly.

## Version 3.1.1

1. Model files are added to the generated source code.
2. `{{! ... }}` escaping symbol added to pattern template helpers. (See [Escaping Symbol](/latest/en/docs/reference-pattern-template-source-helpers/#escaping-symbol))
3. `{{@if ... }}` control structures added to pattern template helpers. (See [Control Structures](/latest/en/docs/reference-pattern-template-source-helpers/#control-structures))
4. Git repository feature is added for pattern templates. Thus, templates can be updated as files. Updated files can be pushed to the Git repository, and these files can be pulled into the pattern templates section with a single click.
5. Some usability improvements are made to the schema, template, and model editors.
6. Some improvements are made on the user interface for better usability.
7. Some styling updates are made on the user interface for better visuality.
8. Patches applied for some parts that are not working correctly.

## Version 3.1.0

1. Project page Files section added. Thus, static files can easily be added for the projects.
2. Git repository setup features are added as a pattern for projects and patterns. If a Git code repository is installed to a project or pattern, source code will be pulled from the Git repository based on its order during source code generation. The source codes pulled from the Git repository will be extracted and copied to the specified directories.
3. Some improvements are made on the user interface for better usability.
4. Some styling updates are made on the user interface for better visuality.

## Version 3.0.0

1. Patterns module added. Users can create their own patterns.
2. Source code editor added. Users can edit source code after code generation.
3. Multilingual user-interface support added.
4. "Edit as JSON" feature added for schemas, templates and models.
5. "Latest Commits" feature added. This feature stores all the previous commits in the browser's `indexedDB` database. With the help of this feature a user can go back to previous commits.
6. Pattern and project versioning feature added.
7. Project multi-pattern support added. A user can choose multiple patterns for a project. Pyronome will generate source code using each pattern at once.