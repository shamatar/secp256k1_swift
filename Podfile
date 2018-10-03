def import_pods
#  pod 'secp256k1_ios', :git => 'https://github.com/shamatar/secp256k1_ios.git', :modular_headers => true
end

target 'secp256k1_swift' do
  use_frameworks!
  platform :osx, '10.10'
  import_pods  
  target 'secp256k1_swiftTests' do
    inherit! :search_paths
    # Pods for testing
  end

end

target 'secp256k1_swift_ios' do
  use_frameworks!
  platform :ios, '9.0'
  import_pods
end
