## Step 4: Run and debug in VS Code

A teammate reports unexpected behavior, so you need to validate execution in the debugger.

### 📖 Theory: Validate behavior with run and debug

Running and debugging are core workflows for console apps. Running confirms expected behavior quickly, and debugging helps inspect values and execution flow when behavior is unclear.

Read more:

- [Debug C# in VS Code](https://code.visualstudio.com/docs/csharp/debugging)
- [Using .NET in VS Code](https://code.visualstudio.com/docs/languages/dotnet)

### ⌨️ Activity: Configure and use debugging

1. Open your console app project in VS Code.

1. Run the app from the terminal with `dotnet run` to confirm it still works.

1. Open Run and Debug and create a launch configuration for your project.

1. Set a breakpoint in `Program.cs`, start debugging, and inspect variable values.

1. Commit the new `.vscode/launch.json` file to your branch.

<details>
<summary>Having trouble? 🤷</summary><br/>

- If the debugger does not start, ensure C# Dev Kit is installed and enabled.
- If no launch profile appears, run the app once and reopen Run and Debug.
- If breakpoints are unbound, make sure the app builds successfully first.

</details>
