### NMatrix
---
https://github.com/SciRuby/nmatrix

```sh
gem install nmatrix

git clone git://github.com/SciRuby/nmatrix.git
cd nmatrix/
gem install bundler
bundle install

wget https://www.apache.org/dist/commons/math/binaries/commons-math3-3.6.1-bin.tar.gz
tar zxvf commons-math3-3.6.1-bin.tar.gz
mkdir ext/nmatrix_java/vendor/
cp commons-math3-3.6.1/commons-math3-3.6.1.jar ext/nmatrix_java/vendor/
mkdir -p ext/nmatrix_java/build/class
mkdir ext/nmatrix_java/target
rake jruby


bundle exec rake compile
bundle exec rake spec

bundle exec rake pry

# pry >
require 'nmatrix'
Nmatrix.new([2, 3], [0, 1, 2, 3, 4, 5], dtype: :int64)
m = N[ 
  [0, 1, 2],
  [3, 4, 5]
  ]
m.inspect


uninitialized constant NArray (NameError)

x[1..3,0..4] = some_other_matrix

```

```ruby

```

```

```


