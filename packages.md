# Packages and PackageControl
#############################

## PackageControl
#################

Install PackageControl by copy & paste the code below into the Sublime console.
The console can be opened by `ctrl+shift+\`` or via `View` -> `Show Console`

`import urllib2,os; pf='Package Control.sublime-package'; ipp=sublime.installed_packages_path(); os.makedirs(ipp) if not os.path.exists(ipp) else None; urllib2.install_opener(urllib2.build_opener(urllib2.ProxyHandler())); open(os.path.join(ipp,pf),'wb').write(urllib2.urlopen('http://sublime.wbond.net/'+pf.replace(' ','%20')).read()); print('Please restart Sublime Text to finish installation')`