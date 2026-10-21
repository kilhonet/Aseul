# Aseul

**A free Windows tool that shows your Claude and Codex usage at a glance, right on the taskbar.**

English · [한국어](README.ko.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [Español](README.es.md) · [Português (Brasil)](README.pt-BR.md) · [Français](README.fr.md)

> This document is a translation. If anything differs, the [Korean version](README.ko.md) is authoritative.

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011-0078D4)
![License](https://img.shields.io/badge/license-Freeware-brightgreen)
[![Download](https://img.shields.io/badge/download-kilho.net-orange)](https://down.kilho.net/aseul?lang=en)

![Aseul screen](images/aseul-en.png)

## Overview

Claude and Codex both have a 5-hour limit and a weekly limit. You have probably hit one in the middle of work, or opened a usage page just to see how much you had left.

Aseul puts a **small circular gauge** on the taskbar, next to the clock. One circle per service: the outer ring is weekly usage, the inner ring is 5-hour usage. Each ring fills clockwise from 12 o'clock as you use it, and goes from green to red as you get close to the limit. One glance tells you whether you are cutting it close.

Click the gauge to open the status window with exact usage, the time left until the next reset, and your usage over the last 7 days. Closing the window leaves the gauge on the taskbar, still updating.

## Features

- **Circular gauge on the taskbar** — a double ring per service (outer = weekly, inner = 5-hour). The left circle is Claude, the right one is Codex.
- **Five colour stages** — each ring is split into five 20 % segments: green, yellow-green, yellow, orange, red. Empty segments are shown faintly, so you always see which colour comes next.
- **Automatic refresh** — checks Claude and Codex usage regularly to keep it up to date.
- **Numbers on hover** — hover over the gauge to see one line per service, such as `Claude : 5% / 50%` (5-hour / weekly).
- **Status window** — 5-hour and weekly usage bars per service, with the time left until each reset.
- **7-day history** — one bar per day showing weekly usage and how much was used that day.
- **Matches the taskbar theme** — on a light taskbar the gauge sits on a black LED panel; on a dark taskbar only the rings are shown. Switching themes takes effect immediately.
- **Only the services you use** — circles are drawn only for signed-in services. If you use only Codex, you see only the Codex circle.
- **Run at startup** — turn it on or off from the right-click menu. The installer turns it on.
- **22 languages** — follows the Windows display language.

## Download / Installation

| Type | Link |
|---|---|
| Installer | [Download](https://down.kilho.net/aseul?lang=en) |
| Portable (ZIP) | [Download](https://down.kilho.net/aseul?lang=en&nosetup) |

The installer starts Aseul as soon as it finishes and turns on Run at startup. For the portable version, unzip it and run `Aseul.exe`.

## Usage

### Getting started

1. Make sure you are signed in to **Claude Code** or **Codex**. Aseul reads your usage through that sign-in (see "Requirements" below).
2. Run Aseul. After a moment a **circular gauge** appears on the taskbar, just left of the notification area.
3. Look at the gauge. The outer ring is weekly usage, the inner ring is 5-hour usage. The fuller the ring and the closer to red, the less you have left.
4. For exact numbers, **hover** over the gauge, or **click** it to open the status window.
5. Close the status window with its close button or **Esc**. The gauge stays and keeps updating.

### Screen layout

**Taskbar gauge**

| Element | Meaning |
|---|---|
| Left circle / right circle | Claude / Codex (signed-in services only) |
| Outer ring | Weekly usage |
| Inner ring | 5-hour usage |
| Ring colour | 0–20 % green, 20–40 % yellow-green, 40–60 % yellow, 60–80 % orange, 80–100 % red |
| Hover | `5-hour % / weekly %` per service |
| Click | Open the status window |
| Right-click | Menu (table below) |

**Right-click menu**

| Menu | What it does |
|---|---|
| **Open status window** | Opens the status window — same as clicking the gauge |
| **Run at startup** (check) | Start automatically when you sign in to Windows |
| **Made by Kilho Oh** | Opens the website |
| **Quit** | Asks "Are you sure you want to exit?" and quits |

**Status window**

| Element | Meaning |
|---|---|
| Service name | Claude, Codex |
| **5h** · **Weekly** bars | Usage — same colours as the gauge, darker as it fills |
| % | Current usage |
| **Resets in …** | Time left until that limit goes back to 0 |
| 7-day chart | Appears in place when you hover over a service |

### Tips for common situations

**Checking what is left before a long task**
Hover over the gauge to see 5-hour / weekly usage right away, such as `Claude : 35% / 72%`. If weekly usage is close to the red segment, you can plan big jobs for after the reset.

**Finding out when a limit resets**
Click the gauge to open the status window. To the right of the 5h and Weekly bars you see the time left, such as **Resets in 2d 21h**.

**Seeing which days you used the most this week**
In the status window, hover over a service (Claude or Codex) to show the last-7-days chart. There is one bar per day, with today on the far right. Bar height is that day's weekly usage; the darker top part is how much it went up that day. Hover over a bar to see the date, weekly usage and that day's increase, such as `10/15(Thu) · 56% (+12%)`.

**Using only Claude or only Codex**
Nothing to set up. Only signed-in services get a circle on the gauge and a section in the status window.

**Using a light taskbar**
A black LED panel sits behind the gauge so the ring colours stay clear. Switch to dark and the panel goes away, leaving just the rings. Theme changes take effect immediately.

**Changing the taskbar size**
When the taskbar height changes, for example with small taskbar buttons or a two-row taskbar, the gauge redraws to fit right away. The circles are tray-icon sized, so they stay sharp on high-DPI monitors.

**Showing the gauge every time the PC starts**
Right-click the gauge → check **Run at startup**. The installer already turns it on. Click it again to turn it off.

**After signing in to Claude Code or Codex again**
Nothing to do in Aseul. The next check picks up the new values and the gauge carries on. Until then the status window shows the last values it received, dimmed.

**Running Aseul before signing in**
If you are signed in to neither Claude Code nor Codex, Aseul shows "No signed-in AI found." and quits. Sign in to either one and run it again.

**Finding the status window again**
The status window does not add its own taskbar button. Clicking the gauge opens it in the middle of the monitor the gauge is on, or brings it to the front if it is already open. Running Aseul a second time also opens the status window instead of starting another copy.

**Quitting Aseul completely**
Right-click the gauge → **Quit** → **Yes**. Closing the status window alone does not quit; the gauge stays.

## Configuration

There is no settings window. The only option is **Run at startup** in the right-click menu; everything else follows the system automatically.

| Item | Follows |
|---|---|
| Run at startup | On for the installer, off for portable — change it from the right-click menu |
| Services shown | Signed-in services (Claude, Codex) |
| Gauge look | The taskbar's light / dark theme |
| Gauge size | Tray icon size (taskbar scaling) |
| Status window | Always dark |
| Display language | Windows display language (22 languages, English otherwise) |

## Requirements

- Windows 10 · Windows 11 (64-bit)
- You must be signed in to **Claude Code** or **Codex**.
  - Claude: signed in to Claude Code with a Claude account
  - Codex: signed in to Codex with a ChatGPT account (API key sign-in has no usage figures, so it is not shown)
- An internet connection is needed to fetch usage.
- No extra runtime is needed. The installer uses administrator rights only during installation.

## Updates

Aseul does **not** update itself. At launch it checks whether a new version exists and shows a notice; pressing **Yes** opens the download page and quits the program. New versions are released manually after internal verification and announced on the [Aseul page](https://kilho.net/aseul). See the [update policy notice](https://en.kilho.net/archives/notice/2940).

## License

Aseul is **freeware**. Use it anywhere — at the office, at home, in government offices, at school — free of charge and without restriction, and redistribute it freely.

## Links

- Website: <https://kilho.net/aseul>
- Forum: <https://kilho.top/forum/qna>
- X (Twitter): <https://www.twitter.com/kilhonet>

© KILHO.NET
