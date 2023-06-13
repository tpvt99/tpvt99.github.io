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