## Step 1: Prepare a C# workspace

Before writing code, your team wants every learner to start with the same C# tooling.

Use this step to confirm your environment is ready and to make workspace extension requirements explicit for future contributors.

<img width="200" alt="descriptive alt text" src="../images/inspectocat.png" />

### 📖 Theory: Why a consistent workspace matters

<!-- GitHub-styled notifications can be used outside of ordered lists. Available options are: NOTE, IMPORTANT, WARNING, TIP, CAUTION -->
<!--
> [!NOTE]
> (Important note or additional information relevant to this section)
 -->

A predictable developer environment reduces setup issues and lets you focus on learning goals. In VS Code, C# language support comes from C# Dev Kit, and workspace recommendations help ensure the extension is installed for anyone opening the repository.

Read more:

- [Getting Started with C# in VS Code](https://code.visualstudio.com/docs/csharp/get-started)
- [Workspace recommended extensions](https://code.visualstudio.com/docs/configure/extensions/extension-marketplace#_workspace-recommended-extensions)
- [Adding features to a devcontainer.json file](https://docs.github.com/en/codespaces/setting-up-your-project-for-codespaces/configuring-dev-containers/adding-features-to-a-devcontainer-file)


### ⌨️ Activity: Configure workspace prerequisites

1. Use the button below to create and open a Codespace for your copy of this exercise.

    [Open in GitHub Codespaces](https://codespaces.new/{{ full_repo_name }}?quickstart=1)

1. Confirm the repository shown in the Codespaces creation page is your copy, then create the Codespace.

1. Open the repository and inspect `.vscode/extensions.json`.

    Confirm it recommends `ms-dotnettools.csdevkit`.

1. Inspect `.devcontainer/devcontainer.json`.

    Confirm `ms-dotnettools.csdevkit` is listed under `customizations.vscode.extensions`.

1. Open the Extensions view and verify **C# Dev Kit** is installed and enabled.

1. Open a terminal and run `dotnet --version` to verify the .NET SDK is available.

1. Update `.vscode/extensions.json` and add `ms-dotnettools.csharp` as an additional recommendation.

1. Commit your workspace configuration update.

<details>
<summary>Having trouble? 🤷</summary><br/>

- If `dotnet` is not found, install the .NET SDK and reopen your terminal.
- If C# Dev Kit is missing, install `ms-dotnettools.csdevkit` from the Extensions view.
- If the repository is in Codespaces, rebuild the container after devcontainer changes.
- If your commit has no changes, verify `ms-dotnettools.csharp` was added to `.vscode/extensions.json`.

</details>
