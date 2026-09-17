# Semantic Programming Language — Visual Studio 2022 Extension

This project packages Semantic Programming Language support as a Visual Studio 2022 VSIX.

## Build the VSIX

1. Install the **Visual Studio extension development** workload in Visual Studio Installer.
2. Open `SemanticProgrammingLanguage.VisualStudio.csproj` in Visual Studio 2022.
3. Select `Debug` or `Release` and `Any CPU`.
4. Choose **Build > Rebuild Solution**.
5. The VSIX should be created at:
   - `bin\Debug\SemanticProgrammingLanguage.VisualStudio.vsix`, or
   - `bin\Release\SemanticProgrammingLanguage.VisualStudio.vsix`.

If the build reports that Visual Studio SDK build targets are missing, reopen Visual Studio Installer and ensure **Visual Studio extension development** is installed.

Project website: https://www.semantic-programming-language.com/
