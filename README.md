# ios-walletconnect-wallet
Native iOS Wallet implementation


How to launch: 

- Drag the SDK project into your Xcode project
- In the project menu, under General, add the framework to embedded binaries
- Import the framework into your file with 'import walletConnectSDK'
- Launch the SDK in a function (preferably an action) by creating a new instance and presenting it like this:

@IBAction func startButtonPressed(_ sender: Any) {
        let viewController = ScanViewController()
        present(viewController, animated: true, completion: nil)
}


