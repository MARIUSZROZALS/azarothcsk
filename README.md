# azarothcsk
mariusz.rozalsk@azarothcsk.pl
Microsoft Visual Studio Solution File, Format Version 12.00
# Visual Studio Version 17
VisualStudioVersion = 17.3.32503.460
MinimumVisualStudioVersion = 10.0.40219.1
Project("{9A19103F-16F7-4668-BE54-9A1E7A4F7556}") = "Microsoft.Extensions.Configuration.AzureAppConfiguration", "src\Microsoft.Extensions.Configuration.AzureAppConfiguration\Microsoft.Extensions.Configuration.AzureAppConfiguration.csproj", "{7B793D44-EC46-4C12-B71F-3A5005290C75}"
EndProject
Project("{9A19103F-16F7-4668-BE54-9A1E7A4F7556}") = "Microsoft.Azure.AppConfiguration.AspNetCore", "src\Microsoft.Azure.AppConfiguration.AspNetCore\Microsoft.Azure.AppConfiguration.AspNetCore.csproj", "{6EAA6031-57AB-4FD0-B36A-019A259846B1}"
EndProject
Project("{9A19103F-16F7-4668-BE54-9A1E7A4F7556}") = "Tests.AzureAppConfiguration", "tests\Tests.AzureAppConfiguration\Tests.AzureAppConfiguration.csproj", "{4CCE5AB2-A5D2-413C-A5AD-FFBE2FECC889}"
EndProject
Project("{9A19103F-16F7-4668-BE54-9A1E7A4F7556}") = "ConfigStoreDemo", "examples\ConfigStoreDemo\ConfigStoreDemo.csproj", "{FEEB5694-F3A1-4B01-86DF-15B7CC43390A}"
EndProject
Project("{9A19103F-16F7-4668-BE54-9A1E7A4F7556}") = "ConsoleApplication", "examples\ConsoleApplication\ConsoleApplication.csproj", "{6725B058-185F-4393-9A0A-9D8B568B99C9}"
EndProject
Project("{9A19103F-16F7-4668-BE54-9A1E7A4F7556}") = "Tests.AzureAppConfiguration.AspNetCore", "tests\Tests.AzureAppConfiguration.AspNetCore\Tests.AzureAppConfiguration.AspNetCore.csproj", "{7A809655-5D64-40AF-9CB8-03BD39BE1A79}"
EndProject
Project("{9A19103F-16F7-4668-BE54-9A1E7A4F7556}") = "Microsoft.Azure.AppConfiguration.Functions.Worker", "src\Microsoft.Azure.AppConfiguration.Functions.Worker\Microsoft.Azure.AppConfiguration.Functions.Worker.csproj", "{C062A08A-CE0E-4099-AAF7-8967F883883E}"
EndProject
Project("{9A19103F-16F7-4668-BE54-9A1E7A4F7556}") = "Tests.AzureAppConfiguration.Functions.Worker", "tests\Tests.AzureAppConfiguration.Functions.Worker\Tests.AzureAppConfiguration.Functions.Worker.csproj", "{A9287214-6689-479F-A9F8-D0C02DE433F0}"
EndProject
Project("{9A19103F-16F7-4668-BE54-9A1E7A4F7556}") = "ConsoleAppWithFailOver", "examples\ConsoleAppWithFailOver\ConsoleAppWithFailOver.csproj", "{A6C611F1-D687-4262-8904-828C239CF2E5}"
EndProject
Project("{2150E333-8FDC-42A3-9474-1A3956D46DE8}") = "Properties", "Properties", "{4EC40BFD-526B-474E-8A7E-EF463FB2D55A}"
	ProjectSection(SolutionItems) = preProject
		AzureAppConfigurationRules.ruleset = AzureAppConfigurationRules.ruleset
	EndProjectSection
EndProject
Global
	GlobalSection(SolutionConfigurationPlatforms) = preSolution
		Debug|Any CPU = Debug|Any CPU
		Release|Any CPU = Release|Any CPU
	EndGlobalSection
	GlobalSection(ProjectConfigurationPlatforms) = postSolution
		{7B793D44-EC46-4C12-B71F-3A5005290C75}.Debug|Any CPU.ActiveCfg = Debug|Any CPU
		{7B793D44-EC46-4C12-B71F-3A5005290C75}.Debug|Any CPU.Build.0 = Debug|Any CPU
		{7B793D44-EC46-4C12-B71F-3A5005290C75}.Release|Any CPU.ActiveCfg = Release|Any CPU
		{7B793D44-EC46-4C12-B71F-3A5005290C75}.Release|Any CPU.Build.0 = Release|Any CPU
		{6EAA6031-57AB-4FD0-B36A-019A259846B1}.Debug|Any CPU.ActiveCfg = Debug|Any CPU
		{6EAA6031-57AB-4FD0-B36A-019A259846B1}.Debug|Any CPU.Build.0 = Debug|Any CPU
		{6EAA6031-57AB-4FD0-B36A-019A259846B1}.Release|Any CPU.ActiveCfg = Release|Any CPU
		{6EAA6031-57AB-4FD0-B36A-019A259846B1}.Release|Any CPU.Build.0 = Release|Any CPU
		{4CCE5AB2-A5D2-413C-A5AD-FFBE2FECC889}.Debug|Any CPU.ActiveCfg = Debug|Any CPU
		{4CCE5AB2-A5D2-413C-A5AD-FFBE2FECC889}.Debug|Any CPU.Build.0 = Debug|Any CPU
		{4CCE5AB2-A5D2-413C-A5AD-FFBE2FECC889}.Release|Any CPU.ActiveCfg = Release|Any CPU
		{4CCE5AB2-A5D2-413C-A5AD-FFBE2FECC889}.Release|Any CPU.Build.0 = Release|Any CPU
		{FEEB5694-F3A1-4B01-86DF-15B7CC43390A}.Debug|Any CPU.ActiveCfg = Debug|Any CPU
		{FEEB5694-F3A1-4B01-86DF-15B7CC43390A}.Debug|Any CPU.Build.0 = Debug|Any CPU
		{FEEB5694-F3A1-4B01-86DF-15B7CC43390A}.Release|Any CPU.ActiveCfg = Release|Any CPU
		{FEEB5694-F3A1-4B01-86DF-15B7CC43390A}.Release|Any CPU.Build.0 = Release|Any CPU
		{6725B058-185F-4393-9A0A-9D8B568B99C9}.Debug|Any CPU.ActiveCfg = Debug|Any CPU
		{6725B058-185F-4393-9A0A-9D8B568B99C9}.Debug|Any CPU.Build.0 = Debug|Any CPU
		{6725B058-185F-4393-9A0A-9D8B568B99C9}.Release|Any CPU.ActiveCfg = Release|Any CPU
		{6725B058-185F-4393-9A0A-9D8B568B99C9}.Release|Any CPU.Build.0 = Release|Any CPU
		{7A809655-5D64-40AF-9CB8-03BD39BE1A79}.Debug|Any CPU.ActiveCfg = Debug|Any CPU
		{7A809655-5D64-40AF-9CB8-03BD39BE1A79}.Debug|Any CPU.Build.0 = Debug|Any CPU
		{7A809655-5D64-40AF-9CB8-03BD39BE1A79}.Release|Any CPU.ActiveCfg = Release|Any CPU
		{7A809655-5D64-40AF-9CB8-03BD39BE1A79}.Release|Any CPU.Build.0 = Release|Any CPU
		{C062A08A-CE0E-4099-AAF7-8967F883883E}.Debug|Any CPU.ActiveCfg = Debug|Any CPU
		{C062A08A-CE0E-4099-AAF7-8967F883883E}.Debug|Any CPU.Build.0 = Debug|Any CPU
		{C062A08A-CE0E-4099-AAF7-8967F883883E}.Release|Any CPU.ActiveCfg = Release|Any CPU
		{C062A08A-CE0E-4099-AAF7-8967F883883E}.Release|Any CPU.Build.0 = Release|Any CPU
		{A9287214-6689-479F-A9F8-D0C02DE433F0}.Debug|Any CPU.ActiveCfg = Debug|Any CPU
		{A9287214-6689-479F-A9F8-D0C02DE433F0}.Debug|Any CPU.Build.0 = Debug|Any CPU
		{A9287214-6689-479F-A9F8-D0C02DE433F0}.Release|Any CPU.ActiveCfg = Release|Any CPU
		{A9287214-6689-479F-A9F8-D0C02DE433F0}.Release|Any CPU.Build.0 = Release|Any CPU
		{A6C611F1-D687-4262-8904-828C239CF2E5}.Debug|Any CPU.ActiveCfg = Debug|Any CPU
		{A6C611F1-D687-4262-8904-828C239CF2E5}.Debug|Any CPU.Build.0 = Debug|Any CPU
		{A6C611F1-D687-4262-8904-828C239CF2E5}.Release|Any CPU.ActiveCfg = Release|Any CPU
		{A6C611F1-D687-4262-8904-828C239CF2E5}.Release|Any CPU.Build.0 = Release|Any CPU
	EndGlobalSection
	GlobalSection(SolutionProperties) = preSolution
		HideSolutionNode = FALSE
	EndGlobalSection
	GlobalSection(ExtensibilityGlobals) = postSolution
		SolutionGuid = {0CBD3139-793B-4B5D-B6CE-ED101C790848}
	EndGlobalSection
EndGlobal
