## Step 3: Add basic input and output

The starter app is too static, so you need to make it interact with the user.

### 📖 Theory: Build interaction with the console

<!-- GitHub-styled notifications can be used outside of ordered lists. Available options are: NOTE, IMPORTANT, WARNING, TIP, CAUTION -->
<!--
> [!NOTE]
> (Important note or additional information relevant to this section)
 -->

Console apps use standard input and output for interaction. Updating `Program.cs` with prompts and responses introduces core C# flow using variables and string interpolation.

Read more:

- [Working with C# in VS Code](https://code.visualstudio.com/docs/languages/csharp)
- [Using .NET in VS Code](https://code.visualstudio.com/docs/languages/dotnet)

### ⌨️ Activity: Personalize the console app

1. Open `Program.cs` in your console app project.

1. Add a prompt asking the user for their name.

1. Read input with `Console.ReadLine()` and store it in a variable.

1. Print a personalized message using string interpolation.

1. Run `dotnet run` and verify the app output includes the text you entered.

1. Commit your changes to `Program.cs`.

<details>
<summary>Having trouble? 🤷</summary><br/>

- If `Console.ReadLine()` returns null, guard with a fallback value.
- If build errors appear, check for missing semicolons and unmatched braces.
- If output looks wrong, re-run and verify interpolation syntax like `$"Hello {name}"`.

</details>
