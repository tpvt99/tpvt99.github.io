# Starting page

### How to serve the page on vscodespace:
1. Navigate to a repo where you have your Jekyll static site (maybe your GitHub pages site)
2. Launch Codespaces (Code button -> Cloud -> New codespace on current branch)
3. Once it's launched, run the following in the terminal

```bash
gem install bundler jekyll
bundle update
bundle exec jekyll serve
```
Now you can head to localhost:port that appears on terminal to see the webpage

### How to install requirements if on your own server
1. Install ruby

Go to https://www.ruby-lang.org/en/downloads/ and download stable verion.

Then extract the `.tar` file to get the folder

After that, do the following commands:

```bash
cd <ruby_directory>
./configure
make
sudo make install
```

1. Following command

```bash
gem install bundler jekyll
bundle update
bundle exec jekyll serve
```

If error says that it depends on something, then you just need `gem install <package>`.
I once got error in rexml package, then I use

```bash
gem install rexml
```

Then run `bundle update` and error gone away


# Understand my personal page 

## Main Page:

index.html is the main page file.

Each of the points in Projects, Publications and Work Experience are data stored under `_data/` folder

The render of each point is inside `_includes/`