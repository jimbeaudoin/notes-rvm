# notes-rvm

### Basic Commands
```sh
rvm get stable #=> Upgrade RVM to the most stable version
rvm current #=> Show current ruby version
rvm --default use 2.1.1 #=> Set default version
rvm gemdir #=> list the full directory path for the current gemset

rvm install 1.9.3 #=> Install ruby version 1.9.3
# INSTALL FROM SOURCE
rvm install ruby-2.2.2 --disable-binary
rvm rubygems current #=> install the most recent RubyGems that RVM knows about

rvm use 2.1.2 #=> Use ruby version 2.1.2
rvm gemset create <gemset_name> #=> Create a new gemset
rvm use 2.1.2@<gemset_name> #=> Use ruby version 2.1.2 with the gemset specified.
rvm gemset use teddy #=> Use the gemset named teddy

rvm gemset list #=> list all named gemsets for the current ruby interpreter
rvm gemset list_all #=> list all named gemsets for all interpreters
rvm gemset empty <gemset_name> #=> removes all gems installed in the gemset
rvm gemset delete teddy #=> Delete the gemset named teddy
```
--
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/80x15.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">notes-rvm</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="http://jim-beaudoin.com" property="cc:attributionName" rel="cc:attributionURL">Jimmy Beaudoin</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
