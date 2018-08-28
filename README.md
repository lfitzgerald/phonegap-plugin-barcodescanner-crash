# phonegap-plugin-barcodescanner-crash
Test project to show bug

Setup 

 cordova platform add ios
 
 cordova build ios
 
 
 Reproduction step
 
 1. Run project
 2. Click "Scan Barcode" button.
 3. After the Camera viewfinder and Access prompt load select the "Don't Allow" option.
 4. Tap the Camera shutter icon.
 5. At this point the app will go into the barcodeScanFailed method and the app will die. 
 
 
 
