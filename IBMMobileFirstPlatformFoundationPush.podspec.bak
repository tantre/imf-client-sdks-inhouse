Pod::Spec.new do |s|
  s.name         = 'PodNamePlaceHolder'
  s.version      = '8.0.0'
  s.license      = "IBM - MobileFirst Platform Foundation 8.0 beta license agreement"
  s.author       = { "IBM MobileFirst platform for iOS Push." => "mobilsdk@us.ibm.com" }
  s.summary      = "Push framework for IBM MobileFirst Platform Foundation"
  s.description  = "Contains push framework for IBM MobileFirst Platform Foundation"
  s.homepage     = "https://mobilefirstplatform.ibmcloud.com/licenses/ipla/"
  s.source       = {:git => '${build.publish.url}/imf-ios-sdk/imf-client-sdks/.git'}
  s.platforms = {
    :ios => "7.0"
  }
  s.dependency 'IBMMobileFirstPlatformFoundation', '~> 8.0'
  s.vendored_frameworks = 'IBMMobileFirstPlatformFoundationPush/Frameworks/IBMMobileFirstPlatformFoundationPush.framework'
  s.xcconfig = { 'OTHER_LDFLAGS' => '-ObjC' }

end