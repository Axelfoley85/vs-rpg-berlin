# README

## Introduction

Welcome to the VS RPG Berlin website repository! This site is built using Hugo, a static site generator. You can view the live website here:
<https://axelfoley85.github.io/vs-rpg-berlin/>

## Making changes

Small changes can be suggested via issues and/or the github interface. Substantial changes should probably be done by setting up hugo locally.

### Prerequisites for setting up hugo locally

- git
- IDE of your choice (e.g. <https://code.visualstudio.com/>)
- Hugo extended (<https://gohugo.io/installation/>)

### Setup

#### Clone the repository

```bash
git clone https://github.com/Axelfoley85/vs-rpg-berlin.git
cd vs-rpg-berlin
```

#### Install submodules

```bash
git submodule update --init --recursive
```

#### Create a new branch

```bash
git checkout -b your-branch-name-that-describes-changes
```

#### Run website locally

```bash
hugo server
```

You should be able to visit the local preview in your browser: <http://localhost:1313/vs-rpg-berlin/>

### Add or configure content

- Modify content files in the `content/` directory for text or page updates.
- Add images to the `static/images` directory.
- Update configurations in the `hugo.toml` file if necessary.

### Test changes locally

- Ensure everything looks correct locally before deploying.

### Commit changes

```bash
git add .
git commit -m "Describe your changes here"
```

### Deploy changes

```bash
git push origin your-branch-name-that-describes-changes
```

### Viewing the Website

The live website is automatically updated upon every push to the main branch.
Visit: <https://axelfoley85.github.io/vs-rpg-berlin/>
