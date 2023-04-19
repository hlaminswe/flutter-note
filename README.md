# flutter-note
# POD files refresh

go into ios folder
delete the Podfile.lock file
rm -rf Pods
pod cache clean --all
pod deintegrate
pod setup
pod install
