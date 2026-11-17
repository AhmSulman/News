# News

A cross-platform news reader built with **.NET MAUI**, targeting Android, iOS, macOS and Windows.

![.NET MAUI](https://img.shields.io/badge/.NET_MAUI-512BD4?style=flat-square&logo=dotnet&logoColor=white)

## Features

- Headlines feed pulled from a news API
- Article cards that open into a full article view
- Shell navigation with an About page

## Structure

```
News/
  Models/NewsApiModels.cs   API response models
  Views/                    HeadlinesView, ArticleItem, ArticleView, AboutView
  Navigator.cs, Settings.cs
```

## Build

Open `News.sln` in Visual Studio 2022 with the .NET MAUI workload installed. Set your news API key in `Settings.cs`, pick a target and run.

See also [The-News](https://github.com/AhmSulman/The-News), a later version with SQLite storage.

## License

MIT
