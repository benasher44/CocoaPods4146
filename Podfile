platform :ios, '8.0'
use_frameworks!

abstract_target 'SharedDeps' do
  pod 'AFNetworking/NSURLConnection'

  target 'PodsNonTrivalDepsTest' do
    pod 'AFNetworking'
    pod 'AFNetworking-RACExtensions'
    pod 'Mailcheck-ObjectiveC'
  end

  target 'PodsNonTrivalDepsTest WatchKit 1 Extension'
end

