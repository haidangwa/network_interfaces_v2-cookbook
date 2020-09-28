source 'https://supermarket.chef.io'

metadata

# this group can be excluded by berks; for example: `berks upload --except test`
group :test do
  cookbook 'fake', path: 'test/fixtures/cookbooks/fake'
  cookbook 'net_setup', path: 'test/fixtures/cookbooks/net_setup'
end
