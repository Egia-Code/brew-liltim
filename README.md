# timo 🕒

> A simple CLI to track time on tasks — perfect for freelancers, devs, or curious humans.

## Homebrew Formula: timo

A tap to install [lil-tim](https://github.com/DavidBernEgia/timo) via Homebrew.

### Install

```sh
brew tap egia-code/timo
brew install timo
```

## Project

Main project is private for now.

### 🛠 Usage

```sh
timo <command> [flags]
```

#### Create Task

```sh
timo create project-x
```

#### Start/Stop Task

```sh
timo start project-x
timo stop project-x
```

#### List Tasks

```sh
timo list
```

or with filter

```sh
timo list --since 01-04-2025
```

or showing barchart breakdown

```sh
timo list --chart
timo list --since 01-04-2024 --chart
```

#### View Info

```sh
timo info project-x
```

#### Generate Report

```sh
timo report --task project-x --range week --since 01-04-2025
```

#### Export Data

```sh
timo export --task project-x --format csv
```

#### Delete All

```sh
timo clean
```

### 🚧 Roadmap

- [x] Core CLI timer functionality
- [x] Task start/stop with log tracking
- [x] Report generation + export (CSV/JSON)
- [x] Bar chart visualization in terminal
- [x] In-memory and persistent tests
- [ ] Optional task tagging
- [ ] Bash/Zsh autocompletion
- [ ] Linking tasks with GitHub/git


