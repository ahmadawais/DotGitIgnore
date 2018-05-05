# DotGitIgnore File

This repo has my go to `.gitignore` file for general purpose.

## Usage

I have a simple command that I run to add this file to any project.

```sh
# Silently add git ignore but if it fails, then show the error.
alias addgitignore="curl --fail --silent --show-error -O https://raw.githubusercontent.com/ahmadawais/WPGulp/master/.gitignore"
```

After that just run `addgitignore`.

## License

MIT ⓒ [Ahmad Awais](https://AhmadAwais.com/).