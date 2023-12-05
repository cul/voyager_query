# Load DSL and set up stages
require 'capistrano/setup'

# Include default deployment tasks
require 'capistrano/deploy'

# Git SCM plugin
require 'capistrano/scm/git'
install_plugin Capistrano::SCM::Git

# Additional modules
require 'capistrano/rails'
require 'capistrano/passenger'
require 'capistrano/cul'
require 'whenever/capistrano'

# Load custom tasks from `lib/capistrano/tasks` if you have any defined
Dir.glob('lib/capistrano/tasks/*.rake').each { |r| import r }