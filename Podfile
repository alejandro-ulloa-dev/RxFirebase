use_frameworks!

target 'RxFirebase_Example' do
  platform :ios, '13.0'

  pod 'RxFirebase/Storage', :path => './'
  pod 'RxFirebase/Firestore', :path => './'
  pod 'RxFirebase/RemoteConfig', :path => './'
  pod 'RxFirebase/Database', :path => './'
  pod 'RxFirebase/Functions', :path => './'
  pod 'RxFirebase/Auth', :git => 'https://github.com/alejandro-ulloa-dev/RxFirebaseAuth.git'

  # Force local pods
  pod 'RxFirebaseStorage', :path => './'
  pod 'RxFirebaseFirestore', :path => './'
  pod 'RxFirebaseRemoteConfig', :path => './'
  pod 'RxFirebaseDatabase', :path => './'
  pod 'RxFirebaseFunctions', :path => './'
  pod 'RxFirebaseAuthentication', :path => './'
end

target 'RxFirebase_Example_tvOS' do
  platform :tvos, '10.0'

  pod 'RxFirebaseStorage', :path => './'
  pod 'RxFirebaseDatabase', :path => './'
  pod 'RxFirebaseAuthentication', :path => './'
end
