🔗 **Live Site:** [https://otaviofbrito.github.io](https://otaviofbrito.github.io)

## Prerequisites

Before you begin, ensure you have the following installed:

- **Ruby** (version 2.7 or higher)
- **RubyGems**
- **Bundler** (`gem install bundler`)
- **Git**

### Installing Ruby

**macOS:**
```bash
brew install ruby
```

**Linux (Ubuntu/Debian):**
```bash
sudo apt-get install ruby-full
```

**Windows:**
Download and install from [RubyInstaller](https://rubyinstaller.org/)

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/otaviofbrito/otaviofbrito.github.io.git
   cd otaviofbrito.github.io
   ```

2. **Install dependencies:**
   ```bash
   bundle install
   ```

## Running Locally

To run the site on your local machine:

```bash
bundle exec jekyll serve
```

Or use the provided script:
```bash
bash tools/run.sh
```

The site will be available at:
- **Local:** `http://localhost:4000`
- **Network:** `http://[your-ip]:4000`

### Development with Live Reload

For automatic browser refresh on changes:
```bash
bundle exec jekyll serve --livereload
```

### Draft Posts

To preview draft posts:
```bash
bundle exec jekyll serve --drafts
```

