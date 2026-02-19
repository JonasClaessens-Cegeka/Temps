## Step 2: Create a console app project

Your team needs a simple command-line starter app as the base for future exercises.

### 📖 Theory: Start from a project template

<!-- GitHub-styled notifications can be used outside of ordered lists. Available options are: NOTE, IMPORTANT, WARNING, TIP, CAUTION -->
<!--
> [!NOTE]
> (Important note or additional information relevant to this section)
 -->

The `dotnet new console` template creates a minimal, runnable app with starter files. It is the fastest way to begin learning core C# structure and build/run flow.

Read more:

- [Using .NET in VS Code](https://code.visualstudio.com/docs/languages/dotnet)
- [Getting Started with C# in VS Code](https://code.visualstudio.com/docs/csharp/get-started)

<img width="200" alt="descriptive alt text" src="../images/inflatocat.png" />


### ⌨️ Activity: Scaffold your first .NET console app

1. Open a terminal at the repository root.

1. Create a folder for your app and switch to it.

    Example: `mkdir src && cd src`.

1. Run `dotnet new console`.

1. Verify the generated files include a `.csproj` file and `Program.cs`.

1. Run `dotnet run` once to validate the starter app.

1. Commit the newly generated project files.

<details>
<summary>Having trouble? 🤷</summary><br/>

- If `dotnet new` fails, check your SDK with `dotnet --version`.
- If files are not visible, refresh Explorer and confirm you are in the expected folder.
- If run fails, restore dependencies with `dotnet restore` and retry.

</details>
