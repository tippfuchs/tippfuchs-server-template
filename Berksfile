#source 'http://api.berkshelf.com'
site :opscode

metadata

# Dependency to make data bag search work with chef solo
cookbook 'chef-solo-search'

# General Dependencies (Common System)

cookbook 'apt',              '~> 2.3.0'
cookbook 'build-essential',  '~> 2.0.0'
cookbook 'openssl',          '~> 1.1.0'

cookbook 'locale',  github: 'hw-cookbooks/locale'
cookbook 'timezone-ii',      '~> 0.2.0'

cookbook 'vim',              '~> 1.1.0'

# Database

cookbook 'tippfuchs-postgresql', '~> 1.0.0', github: 'blackbird07/tippfuchs-postgresql'
cookbook 'database',         '~> 2.0.0'