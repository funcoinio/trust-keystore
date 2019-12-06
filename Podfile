platform :ios, '13.2'

target 'TrustKeystore' do
  use_frameworks!

  pod 'BigInt', '~> 5.0.0', inhibit_warnings: true
  pod 'CryptoSwift', '~> 1.2.0'
  pod 'TrezorCrypto', inhibit_warnings: true
  pod 'TrustCore', :git=>'https://github.com/funcoinio/trust-core', :branch=>'master', inhibit_warnings: true
  pod 'SwiftLint', '~> 0.38.0'

  target 'KeystoreBenchmark'
  target 'TrustKeystoreTests'
end
