# Uncomment the next line to define a global platform for your project
platform :ios, '9.0'

workspace 'ModuleX.xcworkspace'
project 'ModuleX.xcodeproj'


def common_pods
    pod 'CommonUI', :path => 'DevPods/CommonUI'
end

target 'CommonUI_Example' do
    use_frameworks!
    project 'DevPods/CommonUI/Example/CommonUI.xcodeproj'
    common_pods
end

def modulex_pods
    common_pods
end

target 'ModuleX' do
  # Comment the next line if you don't want to use dynamic frameworks
    use_frameworks!
    modulex_pods
  # Pods for ModuleX

end
