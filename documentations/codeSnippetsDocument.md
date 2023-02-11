# Code Snippets Documentation

## Description

A document outlining how to setup code snippets to minimize typing repetitive code over and over again with a code snippet, for platforms like VS Code, Android Studio and Xcode. 

## VS Code

1. Open Visual Studio Code and go to `File` > `Preferences` > `User Snippets`
2. In the User Snippets section, select the language for which you want to create a
snippet or create a new language-specific file.
3. In the selected language file, add a new snippet by using the following format

```json
"Snippet name": {
    "prefix": "snippet-prefix",
    "body": [
        "Code snippet line 1",
        "Code snippet line 2",
        ...
    ],
    "description": "Description of the snippet"
}
```

4. Replace `Snippet name` with a descriptive name for your snippet.
5. Replace `snippet-prefix` with the abbreviation you want to use to trigger the code
snippet.
6. Replace the `body` field with the code vou want to add as a snippet.
7. Replace the `description` field with a brief description of the code snippet.
8. Save the file and close it.

Now vou can use the abbreviation vou specified to insert the code snippet into your code by typing it in the editor and then pressing the `Tab` key.

## Android Studio

1. Open Android Studio and go to Preferences.
2. In the `Settings` window, navigate to `Editor` > `Live Templates`.
3. In the `Live Templates` section, select the group you want to add your template to or create a new group.
4. Click the `+` button in the upper-right corner to create a new live template.
5. In the Abbreviation field, enter a short code that you want to use to trigger the code snippet.
6. In the Description field, provide a brief description of the code snippet.
7. In the Template text field, enter the code you want to add as a template.
8. Click OK to save the template.

Now you can use the abbreviation you specified to insert the code snippet into your code by typing it in the editor and then pressing the `Tab` key.

## Xcode

1. Open Xcode and go to `Window` > `Code Snippets Library`
2. In the Code Snippets Library, right-click in the left panel and select `New Code Snippet`
3. Fill in the `Title` field with a descriptive name for your code snippet.
4. Fill in the `Platform` field with the platform you want your code snippet to be available
on.
5. Fill in the `Language` field with the programming language you want your code snippet
to be written in.
6. Fill in the `Summary` field with a brief description of your code snippet.
7. Fill in the `Completion Shortcut` field with a unique abbreviation for your code
snippet.
8. In the `Code` field, enter the code you want to add as a snippet.
9. Click `Done` to save the code snippet.

Now you can insert the code snippet into your code by typing the completion shortcut and pressing `Tab`. Xcode will replace the shortcut with the code you entered in the Code Snippets Library.