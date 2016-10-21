platform :ios, '9.0'
ENV['COCOAPODS_DISABLE_STATS'] = 'true'

def pods_react
  pod 'React', :path => 'node_modules/react-native', :subspecs => [
    'Core',
    'RCTImage',
    'RCTActionSheet',
    'RCTNetwork',
    'RCTText',
    'RCTWebSocket',
    'RCTLinkingIOS',
    'RCTGeolocation',
    'ART'
  ]
end

target 'ReActionable' do
  use_frameworks!
  pods_react
end
