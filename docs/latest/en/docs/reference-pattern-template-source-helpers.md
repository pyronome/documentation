---
id: reference-pattern-template-source-helpers
title: Pattern Template Source Helpers
sidebar_label: Template Helpers
---

<a id="aHeaderMenuAnchor" data-header-menu="Docs"></a>

Pyronome source code generators are created by pattern templates. Templates created based on the structure and levels of the project model determine how to generate source code according to the project model's content. During the source code generation process, the project model content is scanned by pattern templates; the source code is generated according to the model elements and values. During this process, some special expressions are used to transfer the elements' values from the project model into the source code. These special expressions are called **Template Source Helpers**.

There are three types of template source helpers:
1. Variables
2. Control Structures
3. Escaping Symbol

## Variables

### Global Variables

##### `{{$__globals__/PYRONOME_SHORT_VERSION}}`

This variable holds the short form of the Pyronome version. Example value: `3.1.2`.

##### `{{$__globals__/PYRONOME_VERSION}}`

This variable holds the short form of the Pyronome version. Example value: `3.1.2`.

##### `{{$__globals__/PYRONOME_LONG_VERSION}}`

This variable holds the long form of the Pyronome version. Example value: `3.1.2+20200430.assets/605a822a/cache`.

##### `{{$__globals__/PYRONOME_PROJECT_NAME}}`

This variable holds the project name. Example value: `testproject`

##### `{{$__globals__/PYRONOME_PROJECT_TITLE}}`

This variable holds the project title. Example value: `Test Project`

##### `{{$__globals__/PYRONOME_PROJECT_VERSION}}`

This variable holds the project version. Example value: `0.0.0-dev`

##### `{{$__globals__/PYRONOME_CURRENT_DATETIME}}`

This variable holds the date and time of the source code generation process without any formatting. Example value: `20200802125448`

##### `{{$__globals__/PYRONOME_CURRENT_DATETIME_FORMATTED}}`

This variable holds the date and time of the source code generation process with YYYY-MM-DD HH:MM:SS format. Example value: `2020-08-02 12:54:48`

##### `{{$__globals__/PYRONOME_CURRENT_DATE}}`

This variable holds the date of the source code generation process without any formatting. Example value: `20200802`

##### `{{$__globals__/PYRONOME_CURRENT_TIME}}`

This variable holds the time of the source code generation process without any formatting. Example value: `125448`

##### `{{$__globals__/PYRONOME_CURRENT_YEAR}}`

This variable holds the year of the source code generation process without any formatting. Example value: `2020`

##### `{{$__globals__/PYRONOME_CURRENT_MONTH}}`

This variable holds the month of the source code generation process without any formatting. Example value: `08`

##### `{{$__globals__/PYRONOME_CURRENT_DAY}}`

This variable holds the day of the source code generation process without any formatting. Example value: `02`

##### `{{$__globals__/PYRONOME_CURRENT_HOUR}}`

This variable holds the hour of the source code generation process without any formatting. Example value: `12`

##### `{{$__globals__/PYRONOME_CURRENT_MINUTE}}`

This variable holds the minute of the source code generation process without any formatting. Example value: `54`

##### `{{$__globals__/PYRONOME_PATTERN_NAME}}`

This variable holds the name of the pattern, which is used for source code generation process. Example value: `testpattern`

##### `{{$__globals__/PYRONOME_PATTERN_TITLE}}`

This variable holds the title of the pattern, which is used for source code generation process. Example value: `Test Pattern`

##### `{{$__globals__/PYRONOME_PATTERN_VERSION}}`

This variable holds the version of the pattern, which is used for source code generation process. Example value: `0.0.0-dev`

##### `{{$__globals__/PYRONOME_PROJECT_USER_NAME}}`

This variable holds the name of the user who makes the source code generation.

##### `{{$__globals__/PYRONOME_PROJECT_USER_EMAIL}}`

This variable holds the e-mail address of the user who makes the source code generation.

##### `{{$__globals__/PYRONOME_PROJECT_USER_FULL_NAME}}`

This variable holds the full name (e.g. firstname and lastname) of the user who makes the source code generation.

##### `{{$__globals__/PYRONOME_PROJECT_CREATION_DATETIME}}`

This variable holds the creation date and time of the project without any formatting. Example value: `20200726080645`

##### `{{$__globals__/PYRONOME_PROJECT_CREATION_DATETIME_FORMATTED}}`

This variable holds the creation date and time of the project with YYYY-MM-DD HH:MM:SS format. Example value: `2020-07-26 08:06:45`

##### `{{$__globals__/PYRONOME_PROJECT_CREATION_DATE}}`

This variable holds the creation date of the project without any formatting. Example value: `20200726`

##### `{{$__globals__/PYRONOME_PROJECT_CREATION_TIME}}`

This variable holds the creation time of the project without any formatting. Example value: `080645`

##### `{{$__globals__/PYRONOME_PROJECT_LAST_UPDATE_DATETIME}}`

This variable holds the last update date and time of the project without any formatting. Example value: `20200726080645`

##### `{{$__globals__/PYRONOME_PROJECT_LAST_UPDATE_DATETIME_FORMATTED}}`

This variable holds the last update date and time of the project with YYYY-MM-DD HH:MM:SS format. Example value: `2020-07-26 08:06:45`

##### `{{$__globals__/PYRONOME_PROJECT_LAST_UPDATE_DATE}}`

This variable holds the last update date of the project without any formatting. Example value: `20200726`

##### `{{$__globals__/PYRONOME_PROJECT_LAST_UPDATE_TIME}}`

This variable holds the last update time of the project without any formatting. Example value: `080645`

##### `{{$__globals__/PYRONOME_RANDOM_STRING_2BYTES_LOWERCASE}}`

This variable holds a random text of 2 characters length with lowercase letters and numbers. Example value: `4a`

##### `{{$__globals__/PYRONOME_RANDOM_STRING_4BYTES_LOWERCASE}}`

This variable holds a random text of 4 characters length with lowercase letters and numbers. Example value: `4a69`

##### `{{$__globals__/PYRONOME_RANDOM_STRING_8BYTES_LOWERCASE}}`

This variable holds a random text of 8 characters length with lowercase letters and numbers. Example value: `4a692a27`

##### `{{$__globals__/PYRONOME_RANDOM_STRING_16BYTES_LOWERCASE}}`

This variable holds a random text of 16 characters length with lowercase letters and numbers. Example value: `4a692a2798b3c8fa`

##### `{{$__globals__/PYRONOME_RANDOM_STRING_32BYTES_LOWERCASE}}`

This variable holds a random text of 32 characters length with lowercase letters and numbers. Example value: `4a692a2798b3c8fa4297b7a0d535d06b`

##### `{{$__globals__/PYRONOME_RANDOM_STRING_64BYTES_LOWERCASE}}`

This variable holds a random text of 64 characters length with lowercase letters and numbers.

##### `{{$__globals__/PYRONOME_RANDOM_STRING_2BYTES_UPPERCASE}}`

This variable holds a random text of 2 characters length with uppercase letters and numbers. Example value: `4A`

##### `{{$__globals__/PYRONOME_RANDOM_STRING_4BYTES_UPPERCASE}}`

This variable holds a random text of 4 characters length with uppercase letters and numbers. Example value: `4A69`

##### `{{$__globals__/PYRONOME_RANDOM_STRING_8BYTES_UPPERCASE}}`

This variable holds a random text of 8 characters length with uppercase letters and numbers. Example value: `4A692A27`

##### `{{$__globals__/PYRONOME_RANDOM_STRING_16BYTES_UPPERCASE}}`

This variable holds a random text of 16 characters length with uppercase letters and numbers. Example value: `4A692A2798B3C8FA`

##### `{{$__globals__/PYRONOME_RANDOM_STRING_32BYTES_UPPERCASE}}`

This variable holds a random text of 32 characters length with uppercase letters and numbers. Example value: `4A692A2798B3C8FA4297B7A0D535D06B`

##### `{{$__globals__/PYRONOME_RANDOM_STRING_64BYTES_UPPERCASE}}`

This variable holds a random text of 64 characters length with uppercase letters and numbers.

### Model Variables

```yaml
- project
    - model_list
        - model
            - title
            - property_list
                - property
                    - title     # <-- Let's assume, we are here!
                    - category
```

The following variables can be used to transfer the elements' values to the source code, considering the model above.

##### `{{$__value__}}`

This variable holds the current value of the model node. In this example, this variable returns the value of the `title` element of the `property` element.

In addition;

- `{{$__value__/__uppercase_text__}}`: Returns the value of the `title` element of the `property` element in the above example by converting it to uppercase.
- `{{$__value__/__lowercase_text__}}`: Returns the value of the `title` element of the `property` element in the above example by converting it to lowercase.
- `{{$__value__/__md5_text__}}`: Returns the MD5 text value of the `title` element of the `property` element in the above example.
- `{{$__value__/__sha1_text__}}`: Returns the SHA1 text value of the `title` element of the `property` element in the above example.
- `{{$__value__/__sha1_md5_text__}}`: Returns the SHA1 text value of the MD5 text value of the `title` element of the `property` element in the above example.

##### `{{$__name__}}`

This variable holds the name of the model node. In this example, this variable returns the name of the `title` element of the `property` element.

In addition; just like `{{$__value__}}` variable, the following expressions can be used:
- `{{$__name__/__uppercase_text__}}`
- `{{$__name__/__lowercase_text__}}`
- `{{$__name__/__md5_text__}}`
- `{{$__name__/__sha1_text__}}`
- `{{$__name__/__sha1_md5_text__}}`

##### `{{$__index__}}`

This variable holds the index of the model node starting from zero. In this example, this variable returns the index of the `title` element of the `property` element.

In addition; just like `{{$__value__}}` variable, the following expressions can be used:
- `{{$__index__/__md5_text__}}`
- `{{$__index__/__sha1_text__}}`
- `{{$__index__/__sha1_md5_text__}}`

##### `{{$__index1__}}`

This variable holds the index of the model node starting from one. In this example, this variable returns the index of the `title` element of the `property` element.

In addition; just like `{{$__value__}}` variable, the following expressions can be used:
- `{{$__index1__/__md5_text__}}`
- `{{$__index1__/__sha1_text__}}`
- `{{$__index1__/__sha1_md5_text__}}`

##### `{{$__type__}}`

This variable holds the type of the model node. In this example, this variable returns the type of the `title` element of the `property` element.

In addition; just like `{{$__value__}}` variable, the following expressions can be used:
- `{{$__type__/__uppercase_text__}}`
- `{{$__type__/__lowercase_text__}}`
- `{{$__type__/__md5_text__}}`
- `{{$__type__/__sha1_text__}}`
- `{{$__type__/__sha1_md5_text__}}`

##### `{{$../category/__value__}}`

This expression returns the value of the `category` element, which is at the same level as the current element.

<div class="panelize-infobox infobox-warning">
    <p>
        <strong><i class="fas fa-exclamation-triangle"></i> Warning:</strong>
    </p>
    <p>The expression is stated according to the model given in the example above. In a different model, the expression {{$../category/__value__}} may vary.</p>
</div>

Similarly;
- `{{$../category/__name__}}`: Returns the name of the `category` element, which is at the same level as the current element.
- `{{$../category/__index__}}`: Returns the index -starting from zero- of the `category` element, which is at the same level as the current element.
- `{{$../category/__index1__}}`: Returns the index -starting from one- of the `category` element, which is at the same level as the current element.
- `{{$../category/__type__}}`: Returns the type of the `category` element, which is at the same level as the current element.

In addition; just like `{{$__value__}}` variable, the following expressions can be used:
- `{{$../category/__value__/__uppercase_text__}}`
- `{{$../category/__value__/__lowercase_text__}}`
- `{{$../category/__value__/__md5_text__}}`
- `{{$../category/__value__/__sha1_text__}}`
- `{{$../category/__value__/__sha1_md5_text__}}`

##### `{{$../../../title/__value__}}`

This expression returns the value of the `title` element of the `model` element that contains the parent of the current element.

<div class="panelize-infobox infobox-warning">
    <p>
        <strong><i class="fas fa-exclamation-triangle"></i> Warning:</strong>
    </p>
    <p>The expression is stated according to the model given in the example above. In a different model, the expression {{$../../../title/__value__}} may vary.</p>
</div>

Similarly;
- `{{$../../../title/__name__}}`: Returns the name of the `title` element of the `model` element that contains the parent of the current element.
- `{{$../../../title/__index__}}`: Returns the index -starting from zero- of the `title` element of the `model` element that contains the parent of the current element.
- `{{$../../../title/__index1__}}`: Returns the index -starting from one- of the `title` element of the `model` element that contains the parent of the current element.
- `{{$../../../title/__type__}}`: Returns the type of the `title` element of the `model` element that contains the parent of the current element.

In addition; just like `{{$__value__}}` variable, the following expressions can be used:
- `{{$../../../title/__value__/__uppercase_text__}}`
- `{{$../../../title/__value__/__lowercase_text__}}`
- `{{$../../../title/__value__/__md5_text__}}`
- `{{$../../../title/__value__/__sha1_text__}}`
- `{{$../../../title/__value__/__sha1_md5_text__}}`

### Pattern & Project Variables

[Platform Pattern Variables](/latest/en/docs/platform-patterns/#variables-page) and [Platform Project Variables](/latest/en/docs/platform-projects/#variables-page) are used for data sharing between patterns during the source code generation process. In some cases, it may be necessary to transfer the variable values to the source code. You can transfer these variables into the source code using the prefix `{{$__variables__/`.

**For example:**

- The variable value defined as `MAX_CPU_COUNT` can be transferred into the template source code with the expression `{{$__variables__/MAX_CPU_COUNT}}`.
- The variable value defined as `PUBLIC_API_KEY` can be transferred into the template source code with the expression `{{$__variables__/PUBLIC_API_KEY}}`.

## Control Structures

##### `{{@if...}}`

It is the control structure that enables "IF" control. The logical test statement should be written in the section marked with `...`. You can group logical test expressions with symbols `(` and `)`; You can link `&&` and `||` with logical test operators.

##### `{{@else}}`

It is the control structure that enables "ELSE" control.

##### `{{@elseif...}}`

It is the control structure that enables "ELSE IF" control. The logical test statement should be written in the section marked with `...`. You can group logical test expressions with symbols `(` and `)`; You can link `&&` and `||` with logical test operators.

##### `{{@endif}}`

The control structure indicates that the control sentence that starts with "IF" is ended.

**Example 1:** The following source code, when the expression `{{$__value__}}` is equal to "5":

```php
{{@if {{$__value__}} < "5"}}
VALUE IS LESS THAN 5
{{@elseif {{$__value__}} == "5"}}
VALUE IS EQUAL TO 5
{{@else}}
VALUE IS GREATER THAN 5
{{@endif}}
```

is converted into the following source code by the code generators:

```php
VALUE IS EQUAL TO 5
```

**Example 2:** The following source code, when the expression `{{$type/__value__}}` is equal to "String":

```php
{{@if {{$type/__value__}} == "String"}}
$currentValue = '';
{{@else}}
$currentValue = 0;
{{@endif}}
```

is converted into the following source code by the code generators:

```php
$currentValue = "";
```

**Example 3:** The following source code, when the expression `{{$type/__value__}}` is equal to "String" and `{{$__index__}}` is equal to "0": 

```php
{{@if ({{$type/__value__}} == "String") && ({{$__index__}} == "0")}}
$values = [];
$values[0] = '';
{{@elseif {{$type/__value__}} == "String"}}
$values[{{$__index__}}] = '';
{{@endif}}
```

is converted into the following source code by the code generators:

```php
$values = [];
$values[0] = '';
```

The above source code example can also be written nested in the following format:

```php
{{@if {{$type/__value__}} == "String"}}
{{@if {{$__index__}} == "0"}}
$values = [];
{{@endif}}
$values[{{$__index__}}] = '';
{{@endif}}
```

## Escaping Symbol

The expressions `{{` and `}}`, which have a special meaning for Pyronome pattern templates, can also have a special meaning for many other software languages, frameworks, and libraries. Therefore, in some cases, you may want Pyronome source code generators to ignore the `{{` and `}}` statements. In such cases, you can use the expression `{{!`. The expression `{{!` is converted into `{{` during the source code generation process.

**For example:**

- `{{!name}}` expression is converted into `{{name}}`.
- `{{!$URL}}` expression is converted into `{{$URL}}`.
- `{{!@if}}` expression is converted into `{{@if}}`.