def import_pods
  pod 'CryptoSwift', '~> 1.4.0'
end

target 'scrypt' do
  platform :osx, '11.2'
#  use_frameworks!
  use_modular_headers!
  import_pods

  target 'scryptTests' do
    inherit! :search_paths
    # Pods for testing
  end

  target 'scryptTestsPerf' do
    inherit! :search_paths
    # Pods for testing
  end

end
