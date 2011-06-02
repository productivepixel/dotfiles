# Rakefile - dotfiles configuration repo
#
# Created by Thomas Anderson <thomas@productivepixels.com>
#
# Rake tasks to help setup various *nix systems I work with
#
# Pulls additional packages from Janus and oh-my-zsh
#

namespace :utils do
  desc "Pull 3rd party repos for our setup"
  task :pull do
    puts "Pull 3rd party repos"
  end

  desc "Update 3rd party repos"
  task :update do
    puts "Update repos"
  end

  desc "Add git upstream remote"
  task :upstream do
    puts "ask if we want to track an upstream repo"
  end
end

desc "Setup vim config based on Janus"
namespace :vim do
  task :janus do
    puts "Run janus rake task to update"
  end

  task :local do
    puts "Link local vimrc and gvimrc files to profile"
  end
end

desc "Setup shell to load oh-my-zsh"
namespace :shell do
  task :change do
    puts "Ask the user to permanetly change shell"
  end

  task :zsh do
    puts "Copy zshrc from oh-my-zsh template"
  end
end
