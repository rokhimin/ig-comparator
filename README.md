# Instagram Following-Follower Comparator
Instagram following follower comparator | Jekyll

User can identify accounts they follow but don't follow back

## Live

https://rokhimin.github.io/ig-comparator

[ig-comparator.vercel.app](https://ig-comparator.vercel.app)

## Features

- **Upload Functionality**: Easily upload your Instagram following and follower HTML files.
- **Comparison Results**: Quickly see:
  - Accounts you follow that don't follow you back.
  - Accounts that follow you but you don't follow back.
- **Copy & Download**: Conveniently copy the results to your clipboard or download them as `.txt` files.

## How to Use

1. **Prepare Your Data**:
   - Download your Instagram data by following the tutorial provided in the `read_here.md` file.
2. **Upload Files**:
   - Click on the "Upload Following HTML" button to upload your following list.
   - Click on the "Upload Followers HTML" button to upload your follower list.
3. **Compare**:
   - Press the "Compare" button to process the files and view the results.
4. **Copy or Download**:
   - Use the "Copy" buttons to copy the lists to your clipboard.
   - Use the "Download" buttons to save the lists as `.txt` files.

## Project Structure

- **`_includes/`**: Contains partial templates used in layouts.
- **`_layouts/`**: Holds the main layout templates for the site.
- **`assets/`**: Directory for images, stylesheets, and other static assets.
- **`.gitattributes`**: Git configuration file for attributes.
- **`.gitignore`**: Specifies files and directories to be ignored by Git.
- **`404.html`**: Custom 404 error page.
- **`Gemfile`**: Defines Ruby gem dependencies for the project.
- **`Gemfile.lock`**: Records the exact versions of gems installed.
- **`README.md`**: This file, providing an overview of the project.
- **`_config.yml`**: Main configuration file for the Jekyll site.
- **`index.markdown`**: The homepage content.
- **`read_here.md`**: Tutorial on how to download your Instagram data.

## Contributing

Bug reports and pull requests are welcome on GitHub at [https://github.com/rokhimin/ig-comparator](https://github.com/rokhimin/ig-comparator). This project aims to be a safe and welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](https://www.contributor-covenant.org) code of conduct.

## Development

To set up your environment for development:

1. **Install Dependencies**:
   - Run `bundle install` to install the necessary Ruby gems.
2. **Serve the Site**:
   - Execute `bundle exec jekyll serve` to start the Jekyll server.
   - Open your browser at `http://localhost:4000` to view the site.

## License

This project is open-source and available under the [MIT License](LICENSE).
