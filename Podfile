inhibit_all_warnings!
target 'SorghumYield' do
    pod 'OpenCV', '2.4.9'
    pod 'Firebase', '~>5.2'
    pod 'FirebaseUI', '~>5.0'
    abstract_target 'Tests' do
        target "SorghumYieldTests" do
            pod 'KIF', :configurations => ['Debug']
            pod 'Nimble'
            end
    end
end
