# C# Logging With Serilog And Seq - Structured Logging Made Easy

Structured event logging is so much more than just writing a message to a file. .NET Core natively supports structured event logging. Serilog is a logger that takes advantage of these additional features. Serilog is an easy to configure and easy to use logging system that you can plug into a .NET Core project within minutes. We will configure Serilog, see how to use it in a basic logging scenario.

## Create project

### Add Nuget Packages
```
Install-Package Serilog.AspNetCore
Install-Package Serilog.Settings.Configuration
Install-Package Serilog.Enrichers.Environment
Install-Package Serilog.Enrichers.Thread
Install-Package Serilog.Enrichers.Process
```

<img src="/pictures/json_logs.png" title="json logs"  width="600">
