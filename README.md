### Steps to build a new .aar
 * Clone this repo
 * Open it in Android Studio
 * Update any source files as needed 
 * Build > Clean Project
 * Open the Gradle toolwindow
 * Run barcodescanner > Tasks > other > bundleReleaseAar
 * The (release) .aar will be generated in barcodescanner > build > outputs

### The generated .aar is used in:
* [NativeScript BarcodeScanner Plugin](https://github.com/EddyVerbruggen/nativescript-barcodescanner/)
* [Cordova BarcodeScanner Plugin](https://github.com/Telerik-Verified-Plugins/BarcodeScanner/)
