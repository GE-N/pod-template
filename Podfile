install! 'cocoapods',
:generate_multiple_pod_projects => true,
:incremental_installation => true

${HEADER_PODS}

def module_dependency_pod
  
end

target 'SandboxApp' do
  module_dependency_pod

  pod '${POD_NAME}', :path => '.'

  ${INCLUDED_PODS}

  target '${POD_NAME}Tests' do
    
  end

end

post_install do |installer|

  # Overwriting Header Search Paths
  # overwrite_header_search_path(installer, 'Pods-SandboxApp')

  # Auto Generated Umbrella Header for Internal Modules
  # auto_generate_umbrella_header_modules(installer)
end
