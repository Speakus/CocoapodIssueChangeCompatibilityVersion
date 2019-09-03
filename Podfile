# Podfile syntax here: https://guides.cocoapods.org/syntax/podfile.html
minTarget = '10.0'

def crashPods()
    # for getting useful info about crashes
    pod 'Crashlytics' # Commercial
    pod 'Fabric' # Commercial
end

platform :ios, minTarget
use_frameworks!

# ignore all warnings from all pods
inhibit_all_warnings!

target 'CocoapodIssueChangeCompatibilityVersion' do
  crashPods
end
