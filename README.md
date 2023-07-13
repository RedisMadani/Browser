# SafariMockApp


Welcome to SafariMockApp! This app emulates the Safari web browser on iOS and provides a similar browsing experience. It is implemented using WKWebView and leverages its Key-Value Observing (KVO) and Error Handling features, along with the assistance of WKNavigationDelegate, UIAlertViewController, UIProgressBar, and UIToolBar.

## Features

- **Web Browsing Experience:** Explore a simulated web browsing experience similar to that of Safari.
- **WKWebView with KVO:** Learn how to use WKWebView's KVO capabilities to monitor changes in the web view's properties and respond accordingly.
- **Error Handling:** Understand how to handle errors that occur during web navigation using WKWebView's error handling mechanisms.
- **WKNavigationDelegate:** Discover how to implement the WKNavigationDelegate protocol to customize and control navigation behavior.
- **UIAlertViewController:** Experience the integration of UIAlertViewController for displaying alert messages to the user.
- **UIProgressBar:** Observe the usage of a UIProgressBar to visually indicate the progress of web page loading.
- **UIToolBar:** Interact with a UIToolBar containing common browser actions such as back, forward, and refresh.

## Getting Started

To run SafariMockApp on your device or simulator, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/RedisMadani/SafariMockApp.git
   ```

2. Open the Xcode project file `SafariMockApp.xcodeproj`.

3. Select your desired destination (device or simulator) and click the "Run" button or press `Cmd+R` to build and launch the app.

## Usage

Once you have launched SafariMockApp, you can browse the web and interact with its features:

- Enter a URL in the address bar at the top of the screen and tap the "Go" button to navigate to the specified website.
- Use the back, forward, and refresh buttons in the toolbar to navigate through web pages and reload the current page.
- Observe the UIProgressBar at the top of the screen, which indicates the loading progress of web pages.
- If any errors occur during navigation, an alert message will be displayed using UIAlertViewController.

## Troubleshooting

If you encounter any issues while using SafariMockApp, please try the following troubleshooting steps:

- Ensure that you are running the latest version of Xcode.
- Clean the project (`Shift+Cmd+K`) and rebuild it (`Cmd+B`).
- Delete the app from your device or simulator and reinstall it.
- Check the project's GitHub repository for any open issues or reported bugs.

## Contributing

We welcome contributions to SafariMockApp! If you have any ideas, bug fixes, or new features to propose, please follow these steps:

1. Fork the SafariMockApp repository.
2. Create a new branch based on your changes:
   ```bash
   git checkout -b my-new-feature
   ```
3. Commit your changes with descriptive commit messages:
   ```bash
   git commit -am 'Add a new feature'
   ```
4. Push your branch to GitHub:
   ```bash
   git push origin my-new-feature
   ```
5. Submit a pull request explaining your changes.

Please ensure that your code follows the existing style conventions and includes appropriate tests.

## License

SafariMockApp is released under the [MIT License](https://opensource.org/licenses/MIT). See the LICENSE file for more details.
