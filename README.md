# Ruby/YARD Segfault/Bus Error test

## Instructions:

1. Clone this repo
2. Run "bundle install" to install YARD
3. Run "bundle exec rake -T"
4. Observe the segfault or bus error that occurs. This happens reliably for me on Mac OS X 10.7.3 using Ruby 1.9.2-p290. I'm currently unable to reproduce the problem in Ruby 1.9.3 with this particular simplified sample, but I have seen what appears to be the same issue under 1.9.3 in a larger project.