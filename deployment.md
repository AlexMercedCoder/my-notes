# Application Deployment Notes

## Language Config Files

On heroku the language buildpack will be detected based on the language config file.

| Language | Config File |
|----------|-------------|
| Javascript | package.json |
| Ruby | Gemfile |
| Python | requirements.txt |
| Rust | cargo.toml |
