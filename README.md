# VaultBase

A pre-configured starter vault for Obsidian projects. Use this repository as a base to quickly bootstrap new Obsidian workspaces with a clean structure, ready-to-use templates, Excalidraw integration, and best practices for organization and security. This is **not** intended as a final knowledge base, but as a foundation for your own projects.

## Features

- **Ready-to-use templates** for meetings, daily notes, checklists, and code snippets
- **Excalidraw integration** for visual diagrams and drawings
- **Organized media storage** for images and assets
- **Separation of secrets and environment files**
- **Example folders** to help you get started

## Folder Structure

```
.
├── Home/                # Main notes and example folders
│   ├── @Home.md         # Home note with quick links
│   └── Example Folder*/ # Example notes and organization
├── Excalidraw/          # Excalidraw drawings (.excalidraw.md)
├── _media/              # Images and media assets
├── _templates/          # Note and meeting templates
├── _secrets/            # Sensitive tokens and environment files
│   └── _envs/           # (Empty by default)
├── README.md            # This file
└── .obsidian/           # Obsidian configuration (hidden)
```

## Templates & Usage

Templates are stored in the `_templates/` folder. To use a template, duplicate the file and fill in the placeholders. Examples:

- **Meeting Template** (`template - meeting.md`):

  ```markdown
  # 🤝 Reunião - {{date}}

  ## 🗒️ Pauta

  -

  ## 👥 Participantes

  -

  ## 📋 Decisões Tomadas

  -

  ## 📝 Ações e Responsáveis

  - [ ] Task - Responsible
  ```

- **Daily Note** (`template - daily.md`):

  ```markdown
  # 📅 Daily Note - {{date}}

  ## 📝 Resumo do Dia

  -

  ## 🎯 Objetivos Principais

  - [ ]
  ```

- **Checklist** (`template - checklist.md`):

  ```markdown
  ## {{insert - title}}

  - [ ]
  ```

- **Code Block Snippet** (`snippet - code block.md`):

  ```markdown

  ```

  // your code here

  ```

  ```

## Excalidraw Integration

Store your Excalidraw drawings in the `Excalidraw/` folder. Open `.excalidraw.md` files in Obsidian with the Excalidraw plugin for best experience.

## Media Usage

Place images and other media assets in the `_media/` folder. Reference them in your notes using standard Markdown image syntax:

```markdown
![[_media/Pasted image 20250530144208.png]]
```

## Security Notice

- The `_secrets/` folder is intended for sensitive information (tokens, environment files). **Never commit real secrets to public repositories.**
- The `_secrets/_envs/` folder is empty by default and can be used for environment-specific files.
- The `_secrets/` folder is protected by `.gitignore` and will not be versioned by default.

## Getting Started

1. Clone or copy this vault to your Obsidian workspace.
2. Open with Obsidian.
3. Change the vault title in Obsidian settings to match your project or personal preference.
4. Duplicate templates from `_templates/` as needed.
5. Use the `Home/@Home.md` as your dashboard.

## License

Specify your license here if applicable.

## Credits

Created and maintained by [@philipgomesph](https://github.com/philipgomesph)

## Suggested Plugins

See the [SUGGESTED-PLUGINS.md](./SUGGESTED-PLUGINS.md) file for a curated list of recommended plugins to enhance your Obsidian experience with this vault.
