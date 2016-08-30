# Rake file

namespace :os_10_11 do
  task :chef_12_13_37 do
    sh 'sudo /Applications/AutoDMG.app/Contents/MacOS/AutoDMG --log-level 6 --logfile - build -r --download-updates ../AutoDMG_Templates/operating_system/el_capitan/12.13.37.adtmpl'
  end
  task :chef_12_8_1 do
    sh 'sudo /Applications/AutoDMG.app/Contents/MacOS/AutoDMG --log-level 6 --logfile - build -r --download-updates ../AutoDMG_Templates/operating_system/el_capitan/12.8.1.adtmpl'
  end
end

namespace :tk_10_11 do
  task :chef_12_13_37 do
    sh 'sudo /Applications/AutoDMG.app/Contents/MacOS/AutoDMG --log-level 6 --logfile - build -r  ../AutoDMG_Templates/test_kitchen/el_capitan/12.13.37.adtmpl'
  end
  task :chef_12_8_1 do
    sh 'sudo /Applications/AutoDMG.app/Contents/MacOS/AutoDMG --log-level 6 --logfile - build -r  ../AutoDMG_Templates/test_kitchen/el_capitan/12.8.1.adtmpl'
  end
end

namespace :os_10_10 do
  task :chef_12_13_37 do
    sh 'sudo /Applications/AutoDMG.app/Contents/MacOS/AutoDMG --log-level 6 --logfile - build -r --download-updates ../AutoDMG_Templates/operating_system/yosemite/12.13.37.adtmpl --output /Users/Shared/os_10_10_chef_12_13_37.dmg'
  end
  task :chef_12_8_1 do
    sh 'sudo /Applications/AutoDMG.app/Contents/MacOS/AutoDMG --log-level 6 --logfile - build -r --download-updates ../AutoDMG_Templates/operating_system/yosemite/12.8.1.adtmpl --output /Users/Shared/os_10_10_chef_12_8_1.dmg'
  end
end

namespace :tk_10_10 do
  task :chef_12_13_37 do
    sh 'sudo /Applications/AutoDMG.app/Contents/MacOS/AutoDMG --log-level 6 --logfile - build -r  ../AutoDMG_Templates/test_kitchen/yosemite/12.13.37.adtmpl --output /Users/Shared/tk_10_10_chef_12_13_37.dmg'
  end
  task :chef_12_8_1 do
    sh 'sudo /Applications/AutoDMG.app/Contents/MacOS/AutoDMG --log-level 6 --logfile - build -r  ../AutoDMG_Templates/test_kitchen/yosemite/12.8.1.adtmpl --output /Users/Shared/tk_10_10_chef_12_8_1.dmg'
  end
end

namespace :os_10_9 do
  task :chef_12_13_37 do
    sh 'sudo /Applications/AutoDMG.app/Contents/MacOS/AutoDMG --log-level 6 --logfile - build -r --download-updates ../AutoDMG_Templates/operating_system/mavericks/12.13.37.adtmpl --output /Users/Shared/os_10_9_chef_12_13_37.dmg'
  end
  task :chef_12_8_1 do
    sh 'sudo /Applications/AutoDMG.app/Contents/MacOS/AutoDMG --log-level 6 --logfile - build -r --download-updates ../AutoDMG_Templates/operating_system/mavericks/12.8.1.adtmpl --output /Users/Shared/os_10_9_chef_12_8_1.dmg'
  end
end

namespace :tk_10_9 do
  task :chef_12_13_37 do
    sh 'sudo /Applications/AutoDMG.app/Contents/MacOS/AutoDMG --log-level 6 --logfile - build -r ../AutoDMG_Templates/operating_system/mavericks/12.13.37.adtmpl --output /Users/Shared/tk_10_9_chef_12_13_37.dmg'
  end
  task :chef_12_8_1 do
    sh 'sudo /Applications/AutoDMG.app/Contents/MacOS/AutoDMG --log-level 6 --logfile - build -r ../AutoDMG_Templates/operating_system/mavericks/12.8.1.adtmpl --output /Users/Shared/tk_10_9_chef_12_8_1.dmg'
  end
end

desc 'El Capitan Operating System All'
task el_cap_os_all: ['os_10_11:chef_12_13_37', 'os_10_11:chef_12_8_1']

desc 'El Capitan Operating System 12.13.37'
task el_cap_os_12_13_37: ['os_10_11:chef_12_13_37']

desc 'El Capitan Operating System 12.8.1'
task el_cap_os_12_8_1: ['os_10_11:chef_12_8_1']

desc 'El Capitan Test Kitchen All'
task el_cap_tk_all: ['tk_10_11:chef_12_13_37', 'tk_10_11:chef_12_8_1']

desc 'El Capitan Test Kitchen 12.13.37'
task el_cap_tk_12_13_37: ['tk_10_11:chef_12_13_37']

desc 'El Capitan Test Kitchen 12.8.1'
task el_cap_tk_12_8_1: ['tk_10_11:chef_12_8_1']

desc 'Yosemite Operating System All'
task yosemite_os_all: ['os_10_10:chef_12_13_37', 'os_10_10:chef_12_8_1']

desc 'Yosemite Operating System 12.13.37'
task yosemite_os_12_13_37: ['os_10_10:chef_12_13_37']

desc 'Yosemite Operating System 12.8.1'
task yosemite_os_12_8_1: ['os_10_10:chef_12_8_1']

desc 'Yosemite Test Kitchen All'
task yosemite_tk_all: ['tk_10_10:chef_12_13_37', 'tk_10_10:chef_12_8_1']

desc 'Yosemite Test Kitchen 12.13.37'
task yosemite_tk_12_13_37: ['tk_10_10:chef_12_13_37']

desc 'Yosemite Test Kitchen 12.8.1'
task yosemite_tk_12_8_1: ['tk_10_10:chef_12_8_1']

desc 'Mavericks Operating System All'
task mavericks_os_all: ['os_10_9:chef_12_13_37', 'os_10_9:chef_12_8_1']

desc 'Mavericks Operating System 12.13.37'
task mavericks_os_12_13_37: ['os_10_9:chef_12_13_37']

desc 'Mavericks Operating System 12.8.1'
task mavericks_os_12_8_1: ['os_10_9:chef_12_8_1']

desc 'Mavericks Test Kitchen All'
task mavericks_tk_all: ['tk_10_9:chef_12_13_37', 'tk_10_9:chef_12_8_1']

desc 'Mavericks Test Kitchen 12.13.37'
task mavericks_tk_12_13_37: ['tk_10_9:chef_12_13_37']

desc 'Mavericks Test Kitchen 12.8.1'
task mavericks_tk_12_8_1: ['tk_10_9:chef_12_8_1']
