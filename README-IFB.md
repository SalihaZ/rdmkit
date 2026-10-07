# View RDMkit locally

To preview the *Tool assembly: IFB* page before it is published on [RDMkit](https://rdmkit.elixir-europe.org).

## 1. Get the repository

```bash
git clone https://gitlab.com/ifb-elixirfr/fair/rdmkit.git
cd rdmkit
git checkout update-ifb-tool-assembly
```

## 2. Install Ruby (once)

**Linux (Ubuntu)**

```bash
sudo apt install ruby-full build-essential zlib1g-dev
echo 'export GEM_HOME="$HOME/gems"; export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
```

**macOS** (requires [Homebrew](https://brew.sh))

```bash
brew install ruby
echo 'export GEM_HOME="$HOME/gems"; export PATH="$(brew --prefix)/opt/ruby/bin:$HOME/gems/bin:$PATH"' >> ~/.zshrc
```

Then **close and reopen your terminal**.

## 3. Install Jekyll (once)

From the `rdmkit` folder:

```bash
gem install jekyll bundler
bundle install
```

## 4. Run the site

```bash
bundle exec jekyll serve
```

Open **http://localhost:4000** in your browser. To stop: `Ctrl + C`.
