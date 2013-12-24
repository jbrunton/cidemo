# Podfile

# Select the appropriate platform below
# Specify the minimum supported iOS version (or later) required by Kiwi
platform :ios, '7.0'
# platform :osx

#
# Some other entries might already exist in the file
# ...
#

pod "AFNetworking", "~> 2.0"

# Add Kiwi as an exclusive dependency for the cidemoTests target
# target :cidemoTests, :exclusive => true do
#    pod 'Kiwi'
# end

# If you're using Xcode 5 with a brand new project
# (XCTest based instead of OCUnit based) use this instead:
target :cidemoTests, :exclusive => true do
   pod 'Kiwi/XCTest'
end

