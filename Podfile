# Targeting iOS 6 and above.
platform :ios, '9.3'

# Name of the XCode workspace that will contain the project and the pods.
workspace 'TCGoogleMaps'

# Look for target to link with in an Xcode project called `TCGoogleMaps.xcodeproj`.
xcodeproj 'TCGoogleMaps'

# Link with our main target that builds the app.
link_with 'TCGoogleMaps'

# List of pods that our project links with.
pod 'GoogleMaps'
pod 'AFNetworking'
pod 'MBProgressHUD'
  
# Add OCMock as a dependency for the Unit Tests target only.
target :TCGoogleMapsTests do
  pod 'OCMock'
end
