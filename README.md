# Godot Social Links

A lightweight Jekyll site that powers the official **https://links.godotengine.org** page.

It provides a centralized directory of official Godot-related links, including the Godot Engine, Foundation, Asset Store, Conference, and other official projects.

## Project Structure

```
.
├── _data/
│   └── links.yml      # Social links and categories
├── images/            # Icons and background assets
├── index.html         # Main page
└── CNAME              # GitHub Pages custom domain
```

## Development

### Prerequisites

- Ruby
- Bundler

Install the dependencies:

```bash
bundle install
```

Start the local development server:

```bash
bundle exec jekyll serve
```

The site will be available at:

```
http://localhost:4000
```

## Updating Links

All links are stored in:

```
_data/links.yml
```

Each top-level key represents a section on the page.

Example:

```yaml
Godot Engine:
  - name: Website
    url: https://godotengine.org

  - name: GitHub
    url: https://github.com/godotengine/godot
```

After modifying `links.yml`, Jekyll will automatically regenerate the page.

## Deployment

This repository is designed to be deployed using **GitHub Pages** with Jekyll.

## Contributing

Contributions are welcome!

If you'd like to improve the website, fix bugs, or update links:

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Open a Pull Request with a clear description of your changes.

Please keep changes focused and test them locally before submitting a PR.

## License

See the [LICENSE](LICENSE) file for details.