source "https://rubygems.org"

# --- Núcleo de Jekyll ---
gem "jekyll", "~> 4.3"

# --- Plugins y extensiones ---
group :jekyll_plugins do
  gem "jekyll-email-protect"
end

# --- Reemplazo moderno del viejo Ruby Sass ---
gem "jekyll-sass-converter", "~> 3.0"
gem "sass-embedded"

# --- Dependencias necesarias para Ruby >= 3.4 ---
gem "webrick"
gem "base64"
gem "logger"

# --- Markdown GitHub Flavored ---
gem "kramdown-parser-gfm"

# --- Compatibilidad Windows (no aplica a macOS, pero se deja seguro) ---
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
#gem "wdm", "~> 0.2", if: Gem.win_platform?
