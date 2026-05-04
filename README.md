<h1 align="center"> Windows 11 Dotfiles</h1><p align="center">
  Personal configuration files for my Windows 11 setup.<br>
  Focused on customization, productivity, and making Windows slightly less painful.
</p><hr><h2> Overview</h2>
<p>
This repository contains my dotfiles and configuration setup for Windows 11.
It includes system customization tools, launcher configs, terminal settings,
and development environment tweaks.
<h2> Prerequisites</h2>
<ul>
  <li>JetBrains Mono Nerd Font</li>
</ul>
</p><hr><h2>Toola Used</h2>

<ul>
  <li><b>OS:</b> <a href="https://www.microsoft.com/windows/windows-11">Windows 11</a>  <a href="https://learn.microsoft.com/en-us/windows/wsl/">WSL2</a> </li>
  <li><b>WM:</b><a href="https://github.com/LGUG2Z/komorebi">Komorebi</a> / <a href="https://github.com/glzr-io/glazewm">GlazeWM</a></li>
  <li><b>Shell:</b> <a href="https://learn.microsoft.com/en-us/powershell/">PowerShell</a> / <a href="https://zsh.sourceforge.io/">zsh</a> </li>
  <li><b>Terminal Emulator:</b> <a href="https://github.com/microsoft/terminal">Windows Terminal</a> &gt;_</li>
  <li><b>Panel:</b> <a href="https://github.com/amnweb/yasb">YASB</a> </li>
  <li><b>Text Editor:</b> <a href="https://neovim.io/">Neovim</a> / <a href="https://code.visualstudio.com/">VS Code</a> </li>
  <li><b>App Launcher:</b> <a href="https://www.flowlauncher.com/">Flow Launcher</a> </li>
  <li><b>File Manager:</b> <a href="https://yazi-rs.github.io/">Yazi</a> </li>
  <li><b>System Monitor:</b> <a href="https://github.com/aristocratos/btop">btop</a> </li>
  <li><b>Colorscheme:</b> <a href="https://catppuccin.com/">Catppuccin</a> </li>
</ul>
<hr><h2>Setup</h2>

<blockquote>
<b>⚠️ WARNING:</b> These configs are <b>not plug-and-play</b><br>
Cherry-pick what you need. Backup before applying.
</blockquote>

<details>
<summary><b> GlazeWM</b></summary>
<br>
<ul>
  <li>Install <a href="https://github.com/glzr-io/glazewm/releases">GlazeWM</a></li>
  <li><a href=".config/glazewm/config.yaml"><code>.config/glazewm/config.yaml</code></a></li>
</ul>
</details>

<details>
<summary><b>YASB</b></summary>
<br>
<p><b>NOTE:</b> Requires a Nerd Font (JetBrainsMono Nerd Font recommended).</p>
<ul>
  <li>Install <a href="https://github.com/amnweb/yasb/releases">YASB</a></li>
  <li><a href="yasb/"><code>.config/yasb/</code></a></li>
</ul>
</details>

<details>
<summary><b>&gt;_ Windows Terminal</b></summary>
<br>
<ul>
  <li>Install <a href="https://github.com/microsoft/terminal">Windows Terminal</a></li>
  <li><a href="Windiws-Terminal/settings.json"><code>.config/terminal/settings.json</code></a></li>
</ul>
</details>

<details>
<summary><b> PowerShell</b></summary>
<br>
<ul>
  <li>Install <a href="https://learn.microsoft.com/en-us/powershell/scripting/install/install-powershell">PowerShell</a></li>
  <li><a href="WindowsPowershell/Microsoft.PowerShell_profile.ps1"><code>.config/WindowsPowershell/Microsoft.PowerShell_profile.ps1</code></a></li>
</ul>
</details>

<details>
<summary><b> Zsh</b></summary>
<br>
<p>Available via WSL2 (Ubuntu).</p>
<ul>
  <li><a href="zsh/.zshrc"><code>.config/zsh/.zshrc</code></a></li>
</ul>
</details>

<details>
<summary><b> Oh My Posh</b></summary>
<br>
<ul>
  <li>Install:
    <pre>winget install JanDeDobbeleer.OhMyPosh -s winget</pre>
  </li>
  <li><a href="ohmyposh/theme.toml"><code>.config/ohmyposh/theme.toml</code></a></li>
  <li>Theme init is already included in the PowerShell profile.</li>
</ul>
</details>

<details>
<summary><b> Komorebi</b></summary>


<ul>
<li>Install <a href="[https://github.com/LGUG2Z/komorebi/releases](https://github.com/LGUG2Z/komorebi/releases)">Komorebi</a></li>
<li><a href="Komorebi/"><code>komorebi.json</code></a> (Main config)</li>
<li><a href="applications.yaml"><code>applications.yaml</code></a> (App-specific rules)</li>
</ul>
</details>

<details>
<summary><b>Flow Launcher</b></summary>
<br>
<ul>
  <li>Install <a href="https://www.flowlauncher.com">Flow Launcher</a></li>
  <li><a href="FlowLauncher/"><code>.config/FlowLauncher/settings.json</code></a></li>
</ul>
</details>

<details>
<summary><b> Windhawk</b></summary>
<br>
<ul>
  <li>Install <a href="https://windhawk.net">Windhawk</a></li>
  <li>Required mods:
    <ul>
      <li>Notification Center Styler</li>
      <li>Start Menu Styler</li>
      <li>Taskbar Styler</li>
    </ul>
  </li>
  <li><a href="windhawk/"><code>.config/windhawk/</code></a></li>
  <li>Paste configs via: <b>Mod → Advanced → Mod Settings → Load</b></li>
</ul>
</details>

<details>
<summary><b> Fastfetch</b></summary>
<br>
<ul>
  <li>Install:
    <pre>winget install fastfetch</pre>
  </li>
  <li><a href="fastfetch/config.jsonc"><code>.config/fastfetch/config.jsonc</code></a></li>
</ul>
</details>
<details>
<summary><b>VS Code</b></summary>
<br>
<ul>
  <li>Install <a href="https://code.visualstudio.com/download">VS Code</a></li>
  <li><a href="Vs-Code/settings.json"><code>.config/vscode/settings.json</code></a></li>
</ul>
</details>

<hr><h2> Preview</h2><p align="center">
  <img src="screenshots/Screenshot01.jpg" width="700"><br><br>
  <img src="screenshots/Screenshot02.jpg" width="700"><br><br>
  <img src="screenshots/Screenshot03.jpg" width="700"><br><br>
  <img src="screenshots/Screenshot04.jpg" width="700">
</p><hr><h2> License</h2>
<p>MIT License</p>
