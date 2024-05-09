# Amazon Affiliate Tag Appender

The Amazon Affiliate Tag Appender is a Chrome extension that automatically appends the `tag` parameter to any URL visited on [amazon.com](https://amazon.com).

## Installation

To install the Amazon Affiliate Tag Appender extension locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/cheungaryk/amazon-affiliate-tag-appender.git
   ```

   Alternatively, you may download the code directly by clicking on **<> Code**, and then **Download ZIP** to download the content as a zip file. Unzip the content to a local directory.
2. (Optional) Open [tag_rules.json](tag_rules.json) in a text editor and locate the line containing `"value":`. Change the value after the colon (the current value is my affiliate tag).
3. Open Chrome and go to **chrome://extensions/**.
4. Enable **Developer mode** using the toggle switch in the top right corner.
5. Click on **Load unpacked** and select the directory where you cloned or downloaded the repository.
6. If there are no errors, the extension should now be installed and active in Chrome.

## Validation

1. Open [amazon.com](https://amazon.com) in a Chrome browser tab.
2. Look at the tab's URL. The tag has been appended automatically so it should look like `https://www.amazon.com/?tag=<TAG_NAME>`.
3. Open any products or account info on Amazon and verify that the tag is still present in the URL.
4. Manually the tag value in the URL and press the `ENTER` key. Verify that the tag has been changed back to the original tag value.

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or bug fixes, please open an issue or submit a pull request on GitHub.

## License

This project is licensed under the [MIT License](https://mit-license.org/).
