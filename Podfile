# Uncomment this line to define a global platform for your project
platform :ios, '10.0'

# Uncomment this line if you're using Swift
use_frameworks!

# ignore all warnings from all pods
inhibit_all_warnings!

source 'https://github.com/Marketing-Suite/podSpec.git'
source 'https://github.com/CocoaPods/Specs.git'
source 'https://github.com/mathereconomics/CocoaPodSpecs.git'

target 'phoenix-reader' do

    # logging
    pod 'CocoaLumberjack', '~> 3.1.0'
    pod 'le', '~> 1.1'
    
    # Fabric tools
    pod 'Fabric', '~> 1.6'
    pod 'Crashlytics', '~> 3.8'
    
    # date tools
    pod 'ISO8601DateFormatter', '~> 0.8'
    
    # block functions - these are dope but we don't need them ... yet
    pod 'BlocksKit', '~> 2.2'
    
    # object mapper
    pod 'Mantle', '~> 2.1'
    
    # ad tools
    pod 'Google-Mobile-Ads-SDK', '~> 7.26.0'
    pod 'GoogleAds-IMA-iOS-SDK', '~> 3.6'
    
    # Image caching and loading
    pod 'SDWebImage', '~> 3.7'
    pod 'UIActivityIndicator-for-SDWebImage', '~> 1.2'
    
    #Custom ActivityIndicator
    pod 'MBProgressHUD', '~> 1.0'
    
    #Optimizely
    #pod 'OptimizelySDKiOS', '~> 1.1'

    #Apptentive
    pod 'apptentive-ios', '~> 4.0.9'
    
    # ADB Omniture
    pod 'AdobeMobileSDK', '~> 4.13'
    
    #Experian
    pod 'EMSMobileSDK', '1.1.1'
    
    #Facebook
    pod 'FacebookCore'
    pod 'FacebookLogin'
    pod 'FacebookShare'
    
    # StoreKit framework
    pod 'SwiftyStoreKit', '~> 0.11'

    # Alamofire for Networking
    pod 'Alamofire'
    
    # Mather
    pod 'IOS-Listener', '1.0.2'

    # Swinject
    pod 'Swinject'

    # Facebook for swift
    pod 'FacebookCore'
    pod 'FacebookLogin'
    
    # Google Sign-In for iOS (Swift)
    pod 'GoogleSignIn'

    # Twitter Integration
    pod 'TwitterKit'

    target 'phoenix-readerTests' do
        inherit! :search_paths
        pod 'OCMock'
    end

end

target 'phoenix-readerUITests' do

end

