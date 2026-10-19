🌐 English | [한국어](README.ko.md)

# Hi, I'm Howon Lee

I go by **airtaxi** online (sometimes kck4156, and hoyo321 back in the day).

I'm a developer based in Seoul, South Korea, with a Ph.D. in Computer Engineering from Sunmoon University.
My dissertation was about building an indoor fire response advisory system using multimodal LLM and retrieval-augmented generation.

I mostly work with .NET and C#, and I enjoy Windows development (especially WinUI) and cross-platform apps with Uno Platform.
I also have experience in game and server development.

---

## Notable Projects

### Windows Apps & Utilities

- **[PinStats](https://github.com/airtaxi/PinStats)** - A Windows 10/11 app that shows real-time PC resource usage. Its standout feature is a live usage widget pinned directly into the Windows 11 taskbar, something almost no other system monitor can do.

- **[Deskband11Lib](https://github.com/airtaxi/Deskband11Lib)** - A library for building rich, always-visible taskbar companions on Windows 11. There are similar approaches out there, but this is pretty much the only powerful one packaged as a usable library.

- **[BarPlay](https://github.com/airtaxi/BarPlay)** - A lightweight taskbar media playback widget for Windows 11. Started as a proof-of-concept for Deskband11Lib, but people around me liked it enough that it became a real app.

- **[AT-Installer](https://github.com/airtaxi/AT-Installer)** - A lightweight Windows installer framework built with WinUI 3. The recently added MSIX-to-EXE packaging feature lets any MSIX become a double-click installer with no PowerShell or Developer Mode.

- **[DeskBorder](https://github.com/airtaxi/DeskBorder)** - A Windows utility for virtual desktop users. Move your mouse to the screen edge to switch desktops, and a lot more. I just think the idea is good.

- **[AI Usage Monitor & Switcher](https://github.com/airtaxi/AI-Usage-Monitor-and-Switcher)** - A Windows app for managing and switching Codex, Claude Code, Z.ai, OpenCode Go, and Ollama accounts. It keeps the active account’s remaining usage and pace indicator visible right on the taskbar.

- **[LidGuard](https://github.com/airtaxi/LidGuard)** - Keeps local AI coding agents awake even when you close your laptop lid. There is really nothing else like this out there.

- **[AT-Image-Converter](https://github.com/airtaxi/AT-Image-Converter)** - A batch image converter built with WinUI 3 and Magick.NET. Clean UI with a wide range of supported formats and options.

- **[AT-Batch-Renamer](https://github.com/airtaxi/AT-Batch-Renamer)** - A batch file and folder renamer built with WinUI 3. Stack rename rules as triggers, check every new name and conflict in a live preview before running, and undo afterward. It also shows up directly in the Windows 11 right-click menu, no "Show more options" needed.

- **[ClosedAwake](https://github.com/airtaxi/ClosedAwake)** - A Windows tray app that keeps your laptop awake even after you close the lid. Plenty of tools prevent idle sleep, but almost none solve the lid-close problem. This one does, with a clean UI.

- **[KoreanNumberParser](https://github.com/airtaxi/KoreanNumberParser)** - A .NET library that parses Korean number strings (like `10억4천3백만이십일`) into int/long and back. The differentiator is that it handles mixed Sino-Korean numerals and Arabic digits in the same expression.

- **[YellowInside](https://github.com/airtaxi/YellowInside)** - A Windows app that lets you use Dccon, Arcacon, and Inven stickers in KakaoTalk messenger.

- **[CrispShot](https://github.com/airtaxi/CrispShot)** - A lightweight tray utility that fixes the small background border Windows leaves around `Alt + Print Screen` captures, with an optional soft drop shadow so your screenshots look like macOS window captures.

- **[AutoClipboardSaver](https://github.com/airtaxi/AutoClipboardSaver)** - A system tray app that automatically saves clipboard images to a folder whenever you copy one.

- **[ScreenBrightnessByBattery](https://github.com/airtaxi/ScreenBrightnessByBattery)** - A lightweight app that automatically adjusts screen brightness based on whether you're on battery or AC power, and can prevent sleep when an external monitor is connected.

- **[NamuWikiViewer](https://github.com/airtaxi/NamuWikiViewer)** - An unofficial NamuWiki viewer app built with WinUI 3 and .NET 10, with ad blocking, history, and a clean reading UI.

---

### .NET MAUI Libraries

- **[SuggestingBox.Maui](https://github.com/airtaxi/SuggestingBox.Maui)** - A .NET MAUI editor control with inline mentions, hashtags, tokenized text, and inline image embedding. Type `@` or `#` and a suggestion popup appears; picked items become styled, immutable tokens that the cursor skips over as a single unit. Pasted images can also be inserted as tokens, so text and images live in one editor. Cross-platform across Android, iOS, macOS, and Windows. I wanted something like this for a side project and nothing out there quite fit, so I built it myself.

- **[AnimatedWebP.FFImageLoading.Maui](https://github.com/airtaxi/AnimatedWebP.FFImageLoading.Maui)** - A fork of FFImageLoading.Maui that adds animated WebP playback on top of SkiaSharp's SKCodec. Drop-in replacement, so the namespaces and assembly name stay the same and you only swap the NuGet package. Came out of needing animated WebP in MAUI and finding the original library didn't ship it.

---

### MCP Servers

I also build MCP (Model Context Protocol) servers so AI coding agents can do more from the terminal.

- **[FluentIconsMcp](https://github.com/airtaxi/FluentIconsMcp)** - Search Windows Fluent Icons from your agent. A .NET global tool that exposes Fluent Icons metadata through a stdio MCP server. Useful when developing WinUI apps and you want your AI agent to pick the right icon for FontIcon.

- **[XamlStylerMcp](https://github.com/airtaxi/XamlStylerMcp)** - Format XAML from your agent. Wraps XamlStyler and lets agents format XAML strings, files, or whole directories.

- **[GithubRepoStructureMcp](https://github.com/airtaxi/GithubRepoStructureMcp)** - Fetch GitHub repository directory structures from your agent as a tree view, including private repos with a PAT. Helps agents explore repositories much faster.

- **[PhotoshopMcpServer](https://github.com/airtaxi/PhotoshopMcpServer)** - An MCP server that lets AI assistants control Adobe Photoshop through Windows COM automation.

---

## Stats

<img src="https://github-stats-extended.vercel.app/api?username=airtaxi&show_icons=true&theme=default" alt="GitHub Stats" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=airtaxi&theme=default" alt="GitHub Streak" />
<img src="https://github-stats-extended.vercel.app/api/top-langs/?username=airtaxi&layout=compact&theme=default" alt="Top Languages" />

---

## Guestbook

Feel free to say hi! I'd love to hear from you.

<a href="https://github.com/airtaxi/airtaxi/issues">
  <img src="https://img.shields.io/badge/Leave%20a%20message-Click%20here-blue" alt="Guestbook" />
</a>

Open an issue in my [profile repo](https://github.com/airtaxi/airtaxi/issues) and drop a comment. Anything is welcome.