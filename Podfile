source 'https://github.com/CocoaPods/Specs.git'

def common
	pod 'Alamofire', '~> 4.2'
	pod 'SDWebImage', '~> 3.8'
end

platform :ios, '10.0'
workspace 'Sample'
project 'SampleA/SampleA'
use_frameworks!

target 'SampleA' do
    common
end

# pre_install do |installer|
#     # workaround for https://github.com/CocoaPods/CocoaPods/issues/3289
#     def installer.verify_no_static_framework_transitive_dependencies; end
# end

# post_install do |installer|
#   installer.pods_project.build_configuration_list.build_configurations.each do |configuration|
#     # configuration.build_settings['CLANG_ALLOW_NON_MODULAR_INCLUDES_IN_FRAMEWORK_MODULES'] = 'YES'
#     # configuration.build_settings['SWIFT_VERSION'] = "3.0"
#   end
# end

