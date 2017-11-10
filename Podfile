platform :ios, '11.1'

target 'Immerse' do
  use_frameworks!

  pod "SwiftyCam", git: "https://github.com/brjennin/SwiftyCam.git", commit: "627ddfa6d830148cf9f2ad8253ed23a3701f890b"

  target 'ImmerseTests' do
    inherit! :search_paths

    pod "Quick"
    pod "Nimble"
    pod "Fleet"
  end

  target 'ImmerseUITests' do
    inherit! :search_paths

    pod "Nimble"
  end

end
